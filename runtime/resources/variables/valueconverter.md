**Name:** ValueConverter

**Kind:** ✔ const

**Type:** Readonly<[IValueConverterResource](https://gitbook-18.gitbook.io/au//runtime/resources/value-converter/interfaces/ivalueconverterresource)>

**Initializer:**

Object.freeze({
name: 'value-converter',
keyFrom(name: string): string {
return `${ValueConverter.name}:${name}`;
},
isType<T>(Type: T & Partial<IValueConverterType>): Type is T & IValueConverterType {
return Type.kind === ValueConverter;
},
define<T extends Constructable = Constructable>(nameOrDefinition: string | IValueConverterDefinition, ctor: T): T & IValueConverterType<T> {
const Type = ctor as T & IValueConverterType<T>;
const WritableType = Type as T & Writable<IValueConverterType<T>>;
const description = createCustomValueDescription(typeof nameOrDefinition === 'string' ? { name: nameOrDefinition } : nameOrDefinition, Type);

WritableType.kind = ValueConverter;
WritableType.description = description;
WritableType.aliases = Type.aliases == null ? PLATFORM.emptyArray : Type.aliases;
Type.register = function register(container: IContainer): void {
const aliases = description.aliases;
const key = ValueConverter.keyFrom(description.name);
Registration.singleton(key, this).register(container);
Registration.alias(key, this).register(container);
registerAliases([...aliases, ...this.aliases], ValueConverter, key, container);
};

return Type;
},
})

