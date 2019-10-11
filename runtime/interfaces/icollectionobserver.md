**Name:** ICollectionObserver

**Extends:** **Name:** ICollectionChangeTracker<CollectionKindToType<T>>

**Type:** <<T>>

, **Name:** ICollectionSubscriberCollection

**Type:**

, **Name:** IBatchable

**Type:**

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends CollectionKind

**Constraint:**

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** inBatch

**Type:** boolean

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** lifecycle

**Type:** [ILifecycle](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/ilifecycle)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** persistentFlags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** collection

**Type:** [ObservedCollectionKindToType](https://gitbook-18.gitbook.io/au//runtime/observation/typealiases/observedcollectionkindtotype)<T>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** lengthObserver

**Type:** T extends [CollectionKind.array](https://gitbook-18.gitbook.io/au//runtime/observation/collectionkind.array) ? [ICollectionLengthObserver](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionlengthobserver) : [ICollectionSizeObserver](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsizeobserver)

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getLengthObserver

**Return Type:** T extends [CollectionKind.array](https://gitbook-18.gitbook.io/au//runtime/observation/collectionkind.array) ? [ICollectionLengthObserver](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionlengthobserver) : [ICollectionSizeObserver](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/icollectionsizeobserver)

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** notify

**Return Type:** void

```

