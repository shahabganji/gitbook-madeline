**Name:** ITemplate

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
**Name:** renderContext

**Type:** [IRenderContext](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/irendercontext)<T>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dom

**Type:** [IDOM](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/idom)<T>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** definition

**Type:** TemplateDefinition

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
**Name:** controller

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

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

**Type:** Record<string, [ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)>

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** render

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** viewModel

**Type:** [IViewModel](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iviewmodel)<T>

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

**Type:** Record<string, [ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)>

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

