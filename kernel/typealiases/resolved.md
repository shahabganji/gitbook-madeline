**Name:**

Resolved

**Type:**

(
K extends [InterfaceSymbol](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/interfacesymbol)<infer T>
? T
: K extends [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable)
? InstanceType<K>
: K extends IResolverLike<any, infer T1>
? T1 extends [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable)
? InstanceType<T1>
: T1
: K
)

**Initializer:**

(
K extends InterfaceSymbol<infer T>
? T
: K extends Constructable
? InstanceType<K>
: K extends IResolverLike<any, infer T1>
? T1 extends Constructable
? InstanceType<T1>
: T1
: K
)

**Type Parameter(s):**

```**Name:**

K

**Text:**

K

```

