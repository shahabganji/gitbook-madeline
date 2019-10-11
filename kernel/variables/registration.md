**Name:** Registration

**Kind:** ✔ const

**Type:** Readonly<{ instance<T>(key: , value: T): <T>; singleton<T extends <{}>>(key: , value: T): <InstanceType<T>>; transient<T extends <{}>>(key: , value: T): <InstanceType<T>>; callback<T>(key: , callback: <T>): <T extends <infer T> ? T : T extends <{}> ? InstanceType<T> : T extends IResolverLike<any, infer T1> ? T1 extends <{}> ? InstanceType<T1> : T1 : T>; alias<T>(original[Key](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/key): T, alias[Key](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/key): ): <T extends <infer T> ? T : T extends <{}> ? InstanceType<T> : T extends IResolverLike<any, infer T1> ? T1 extends <{}> ? InstanceType<T1> : T1 : T>; defer(key: , ...params: unknown[]): ; }>

**Initializer:**

Object.freeze({
instance<T>(key: Key, value: T): IRegistration<T> {
return new Resolver(key, ResolverStrategy.instance, value);
},
singleton<T extends Constructable>(key: Key, value: T): IRegistration<InstanceType<T>> {
return new Resolver(key, ResolverStrategy.singleton, value);
},
transient<T extends Constructable>(key: Key, value: T): IRegistration<InstanceType<T>> {
return new Resolver(key, ResolverStrategy.transient, value);
},
callback<T>(key: Key, callback: ResolveCallback<T>): IRegistration<Resolved<T>> {
return new Resolver(key, ResolverStrategy.callback, callback);
},
alias<T>(originalKey: T, aliasKey: Key): IRegistration<Resolved<T>> {
return new Resolver(aliasKey, ResolverStrategy.alias, originalKey);
},
defer(key: Key, ...params: unknown[]): IRegistry {
return new ParameterizedRegistry(key, params);
}
})

