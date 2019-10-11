**Name:** INavigatorOptions

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** viewer

**Type:** [INavigatorViewer](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/inavigatorviewer)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** store

**Type:** [INavigatorStore](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/inavigatorstore)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** statefulHistoryLength

**Type:** number

**Attributes:** ✔ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instruction

**Type:** [INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** serializeCallback

**Return Type:** Promise<[IStoredNavigatorEntry](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/istorednavigatorentry)>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** entry

**Type:** [IStoredNavigatorEntry](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/istorednavigatorentry)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** entries

**Type:** [IStoredNavigatorEntry](https://gitbook-18.gitbook.io/au//router/navigator/interfaces/istorednavigatorentry)[]

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

