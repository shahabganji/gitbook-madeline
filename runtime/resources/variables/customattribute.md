**Name:** CustomAttribute

**Kind:** ✔ const

**Type:** Readonly<[ICustomAttributeResource](https://gitbook-18.gitbook.io/au//runtime/resources/custom-attribute/interfaces/icustomattributeresource)>

**Initializer:**

Object.freeze({
name: 'custom-attribute',
keyFrom(name: string): string {
return `${CustomAttribute.name}:${name}`;
},
isType<T>(Type: T & Partial<ICustomAttributeType>): Type is T & ICustomAttributeType {
return Type.kind === CustomAttribute;
},
define<T extends Constructable = Constructable>(nameOrDefinition: string | IAttributeDefinition, ctor: T): T & ICustomAttributeType<T> {
const Type = ctor as T & ICustomAttributeType<T>;
const WritableType = Type as T & Writable<ICustomAttributeType<T>>;
const description = createCustomAttributeDescription(typeof nameOrDefinition === 'string' ? { name: nameOrDefinition } : nameOrDefinition, Type);

WritableType.kind = CustomAttribute;
WritableType.description = description;
WritableType.aliases = Type.aliases == null ? PLATFORM.emptyArray : Type.aliases;
Type.register = function register(container: IContainer): void {
const aliases = description.aliases;
const key = CustomAttribute.keyFrom(description.name);
Registration.transient(key, this).register(container);
Registration.alias(key, this).register(container);
registerAliases([...aliases, ...this.aliases], CustomAttribute, key, container);
};

return Type;
},
})

