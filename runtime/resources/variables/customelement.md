**Name:** CustomElement

**Kind:** ✔ const

**Type:** Readonly<[ICustomElementResource](https://gitbook-18.gitbook.io/au//runtime/resources/custom-element/interfaces/icustomelementresource)>

**Initializer:**

Object.freeze({
name: 'custom-element',
keyFrom(name: string): string {
return `${CustomElement.name}:${name}`;
},
isType<T>(Type: T & Partial<ICustomElementType>): Type is T & ICustomElementType {
return Type.kind === CustomElement;
},
behaviorFor<T extends INode = INode>(node: T): IController<T> | undefined {
return (node as CustomElementHost<T>).$controller;
},
define<T extends Constructable = Constructable>(nameOrDefinition: string | ITemplateDefinition, ctor: T | null = null): T & ICustomElementType<T> {
if (!nameOrDefinition) {
throw Reporter.error(70);
}
const Type = (ctor == null ? class HTMLOnlyElement { /* HTML Only */ } : ctor) as T & ICustomElementType<T>;
const WritableType = Type as Writable<ICustomElementType<T>>;
const description = buildTemplateDefinition(Type, nameOrDefinition);

WritableType.kind = CustomElement;
WritableType.description = description;
WritableType.aliases = Type.aliases == null ? PLATFORM.emptyArray : Type.aliases;
Type.register = function register(container: IContainer): void {
const aliases = description.aliases;
const key = CustomElement.keyFrom(description.name);
Registration.transient(key, this).register(container);
Registration.alias(key, this).register(container);
registerAliases([...aliases, ...this.aliases], CustomElement, key, container);

};

return Type;
},
})

