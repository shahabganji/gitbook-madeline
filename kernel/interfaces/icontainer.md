**Name:** IContainer

**Extends:** **Name:** IServiceLocator

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** id

**Type:** number

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** register

**Return Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** params

**Type:** any[]

**Attributes:** ✔ Optional✔ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** registerResolver

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<T>

**Type Parameter(s):**

```**Name:**

K

**Text:**

K extends Key

**Constraint:**

```

```**Name:**

T

**Text:**

T = K

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** key

**Type:** K

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** resolver

**Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** registerTransformer

**Return Type:** boolean

**Type Parameter(s):**

```**Name:**

K

**Text:**

K extends Key

**Constraint:**

```

```**Name:**

T

**Text:**

T = K

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** key

**Type:** K

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** transformer

**Type:** [Transformer](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/transformer)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getResolver

**Return Type:** [IResolver](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iresolver)<T> | null

**Type Parameter(s):**

```**Name:**

K

**Text:**

K extends Key

**Constraint:**

```

```**Name:**

T

**Text:**

T = K

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** key

**Type:** K | Key

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** autoRegister

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getFactory

**Return Type:** [IFactory](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/ifactory)<T>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** key

**Type:** T

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** createChild

**Return Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer)

```

