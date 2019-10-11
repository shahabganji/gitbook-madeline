**Name:** createElement

**Return Type:** [RenderPlan](https://gitbook-18.gitbook.io/au//runtime-html/create-element/classes/renderplan)<T>

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends INode = Node

**Constraint:**

```

```**Name:**

C

**Text:**

C extends Constructable = Constructable

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
dom
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[IDOM](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/idom)<T>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
tagOrType
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string | C

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
props
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**Record<string, string | HTMLTargetedInstruction>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
children
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**ArrayLike<unknown>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

