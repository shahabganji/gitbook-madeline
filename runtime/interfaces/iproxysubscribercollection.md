**Name:** IProxySubscriberCollection

**Extends:** **Name:** IProxySubscribable

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _proxySubscriberFlags

**Type:** [SubscriberFlags](https://gitbook-18.gitbook.io/au//runtime/observation/subscriberflags)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _proxySubscriber0

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _proxySubscriber1

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _proxySubscriber2

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _proxySubscribersRest

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)[]

**Attributes:** ✔ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callProxySubscribers

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** key

**Type:** PropertyKey

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** newValue

**Type:** unknown

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** previousValue

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
**Name:** hasProxySubscribers

**Return Type:** boolean

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hasProxySubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** removeProxySubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addProxySubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [IProxySubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iproxysubscriber)

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

