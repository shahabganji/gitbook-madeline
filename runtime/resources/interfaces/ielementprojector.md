**Name:** IElementProjector

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends INode = INode

**Constraint:**

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** host

**Type:** [CustomElementHost](https://gitbook-18.gitbook.io/au//runtime/resources/custom-element/typealiases/customelementhost)<T>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** children

**Type:** ArrayLike<[CustomElementHost](https://gitbook-18.gitbook.io/au//runtime/resources/custom-element/typealiases/customelementhost)<T>>

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** provideEncapsulationSource

**Return Type:** T

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** project

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nodes

**Type:** [INodeSequence](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inodesequence)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** take

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nodes

**Type:** [INodeSequence](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inodesequence)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscribeToChildrenChange

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Type:** () => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** options

**Type:** any

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

