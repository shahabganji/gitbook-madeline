**Name:** ISignaler

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** signals

**Type:** Record<string, Set<[ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)>>

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dispatchSignal

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** Signal

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

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
**Name:** addSignalListener

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** Signal

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** listener

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** removeSignalListener

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** Signal

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** listener

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

