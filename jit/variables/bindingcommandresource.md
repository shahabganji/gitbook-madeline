**Name:** BindingCommandResource

**Kind:** ✔ const

**Type:** Readonly<[IBindingCommandResource](https://gitbook-18.gitbook.io/au//jit/binding-command/interfaces/ibindingcommandresource)>

**Initializer:**

Object.freeze({
name: 'binding-command',
keyFrom(name: string): string {
return `${BindingCommandResource.name}:${name}`;
},
isType<T>(Type: T & Partial<IBindingCommandType>): Type is T & IBindingCommandType {
return Type.kind === BindingCommandResource;
},
define<T extends Constructable>(nameOrDefinition: string | IBindingCommandDefinition, ctor: T): T & IBindingCommandType {
const Type = ctor as T & IBindingCommandType;
const WritableType = Type as T & Writable<IBindingCommandType>;
const description = createBindingCommandDescription(typeof nameOrDefinition === 'string' ? { name: nameOrDefinition, type: null } : nameOrDefinition, Type);

WritableType.kind = BindingCommandResource;
WritableType.description = description;

Type.register = function register(container: IContainer): void {
const aliases = description.aliases;
const key = BindingCommandResource.keyFrom(description.name);
Registration.singleton(key, Type).register(container);
Registration.alias(key, Type).register(container);
registerAliases([...aliases, ...this.aliases], BindingCommandResource, key, container);
};

return Type;
},
})

