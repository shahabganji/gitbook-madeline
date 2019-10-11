**Name:** IFactory

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable = any

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** Type

**Type:** T

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** registerTransformer

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** transformer

**Type:** [Transformer](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/transformer)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** construct

**Return Type:** Resolved<T>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** container

**Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dynamicDependencies

**Type:** [Key](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/key)[]

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

