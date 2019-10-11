**Name:** BindingBehavior

**Kind:** ✔ const

**Type:** Readonly<[IBindingBehaviorResource](https://gitbook-18.gitbook.io/au//runtime/resources/binding-behavior/interfaces/ibindingbehaviorresource)>

**Initializer:**

Object.freeze({
name: 'binding-behavior',
keyFrom(name: string): string {
return `${BindingBehavior.name}:${name}`;
},
isType<T>(Type: T & Partial<IBindingBehaviorType>): Type is T & IBindingBehaviorType {
return Type.kind === BindingBehavior;
},
define<T extends Constructable = Constructable>(nameOrDefinition: string | IBindingBehaviorDefinition, ctor: T): T & IBindingBehaviorType<T> {
const Type = ctor as T & IBindingBehaviorType<T>;
const WritableType = Type as T & Writable<IBindingBehaviorType<T>>;
const description = createBindingBehaviorDescription(typeof nameOrDefinition === 'string' ? { name: nameOrDefinition } : nameOrDefinition, Type);

WritableType.kind = BindingBehavior;
WritableType.description = description;
WritableType.aliases = Type.aliases == null ? PLATFORM.emptyArray : Type.aliases;
Type.register = function register(container: IContainer): void {
const aliases = description.aliases;
const key = BindingBehavior.keyFrom(description.name);
Registration.singleton(key, this).register(container);
Registration.alias(key, this).register(container);
registerAliases([...aliases, ...this.aliases], BindingBehavior, key, container);
};

return Type;
},
})

