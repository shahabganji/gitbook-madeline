**Name:** ICollectionSubscriberCollection

**Extends:** **Name:** ICollectionSubscribable

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _collectionSubscriberFlags

**Type:** [SubscriberFlags](https://gitbook-18.gitbook.io/au//runtime/observation/subscriberflags)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _collectionSubscriber0

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _collectionSubscriber1

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _collectionSubscriber2

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** _collectionSubscribersRest

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)[]

**Attributes:** ✔ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callCollectionSubscribers

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** indexMap

**Type:** [IndexMap](https://gitbook-18.gitbook.io/au//runtime/observation/typealiases/indexmap)

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
**Name:** hasCollectionSubscribers

**Return Type:** boolean

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hasCollectionSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** removeCollectionSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addCollectionSubscriber

**Return Type:** boolean

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscriber

**Type:** [ICollectionSubscriber](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsubscriber)

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

