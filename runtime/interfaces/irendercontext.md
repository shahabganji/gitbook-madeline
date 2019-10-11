**Name:** IRenderContext

**Extends:** **Name:** IContainer

**Type:**

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
**Name:** parentId

**Type:** number

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** render

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** renderable

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** targets

**Type:** ArrayLike<object>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** templateDefinition

**Type:** TemplateDefinition

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** host

**Type:** T

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parts

**Type:** TemplatePartDefinitions

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** beginComponentOperation

**Return Type:** [IDisposable](https://gitbook-18.gitbook.io/au//kernel/interfaces/interfaces/idisposable)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** renderable

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** target

**Type:** object

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [ITargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itargetedinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** factory

**Type:** [IViewFactory](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iviewfactory)<T> | null

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parts

**Type:** TemplatePartDefinitions

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** location

**Type:** [IRenderLocation](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/irenderlocation)<T>

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** locationIsContainer

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

