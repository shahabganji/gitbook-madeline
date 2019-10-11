**Name:** IResolverBuilder

**Type Parameter(s):**

```**Name:**

K

**Text:**

K

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instance

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<K>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** K

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** singleton

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<K>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** transient

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<K>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<K>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** [ResolveCallback](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/resolvecallback)<K>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** aliasTo

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<K>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** destinationKey

**Type:** [Key](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/key)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

