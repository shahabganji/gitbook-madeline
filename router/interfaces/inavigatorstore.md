**Name:** INavigatorStore

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** length

**Type:** number

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** state

**Type:** Record<string, unknown>

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** go

**Return Type:** Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** delta

**Type:** number

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** suppressPopstate

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** pushNavigatorState

**Return Type:** Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** state

**Type:** [INavigatorState](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/inavigatorstate)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** replaceNavigatorState

**Return Type:** Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** state

**Type:** [INavigatorState](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/inavigatorstate)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** popNavigatorState

**Return Type:** Promise<void>

```

