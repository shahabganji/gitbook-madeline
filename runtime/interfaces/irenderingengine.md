**Name:** IRenderingEngine

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getElementTemplate

**Return Type:** [ITemplate](https://gitbook-18.gitbook.io/au//runtime/rendering-engine/interfaces/itemplate)<T>|undefined

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends INode = INode

**Constraint:**

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dom

**Type:** [IDOM](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/idom)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** definition

**Type:** TemplateDefinition

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parentContext

**Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer) | [IRenderContext](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/irendercontext)<T>

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** componentType

**Type:** [ICustomElementType](https://gitbook-18.gitbook.io/au//runtime/resources/custom-element/interfaces/icustomelementtype)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getViewFactory

**Return Type:** [IViewFactory](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iviewfactory)<T>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends INode = INode

**Constraint:**

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dom

**Type:** [IDOM](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/idom)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** source

**Type:** [ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parentContext

**Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer) | [IRenderContext](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/irendercontext)<T>

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

