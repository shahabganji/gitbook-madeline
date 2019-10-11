**Name:** IViewCache

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
**Name:** isCaching

**Type:** boolean

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** setCacheSize

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** size

**Type:** number | '*'

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** doNotOverrideIfAlreadySet

**Type:** boolean

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** canReturnToCache

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** view

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** tryReturnToCache

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** view

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

