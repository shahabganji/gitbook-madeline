**Name:** IViewFactory

**Extends:** **Name:** IViewCache<T>

**Type:** <T>

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
**Name:** parentContextId

**Type:** number

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parts

**Type:** TemplatePartDefinitions

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** create

**Return Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addParts

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parts

**Type:** TemplatePartDefinitions

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

