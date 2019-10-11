**Name:** IRouteableComponent

**Extends:** **Name:** IViewModel<T>

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
**Name:** reentryBehavior

**Type:** [ReentryBehavior](https://gitbook-18.gitbook.io/au//router/interfaces/enums/reentrybehavior)

**Attributes:** ✔ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** canEnter

**Return Type:** boolean | string | [ViewportInstruction](https://gitbook-18.gitbook.io/au//router/viewport-instruction/classes/viewportinstruction)[] | Promise<boolean | string | [ViewportInstruction](https://gitbook-18.gitbook.io/au//router/viewport-instruction/classes/viewportinstruction)[]>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parameters

**Type:** string[] | Record<string, string>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nextInstruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** enter

**Return Type:** void | Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parameters

**Type:** string[] | Record<string, string>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nextInstruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** canLeave

**Return Type:** boolean | Promise<boolean>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nextInstruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction) | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** leave

**Return Type:** void | Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nextInstruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction) | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

