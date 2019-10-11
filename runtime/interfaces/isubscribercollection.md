**Name:** ISubscriberCollection

**Extends:** **Name:** ISubscribable

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _subscriberFlags

**Type:** [SubscriberFlags](https://gitbook-18.gitbook.io/au//runtime/observation/subscriberflags)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _subscriber0

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _subscriber1

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _subscriber2

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _subscribersRest

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)[]

**Attributes:** ✔ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callSubscribers

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** newValue

**Type:** unknown

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** oldValue

**Type:** unknown

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hasSubscribers

**Return Type:** boolean

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hasSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** removeSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ISubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/isubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

❱❱&nbsp;&nbsp;**Indexer(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Key:** key

**Value:** number

**Return Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

```

