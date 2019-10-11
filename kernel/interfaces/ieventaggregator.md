**Name:** IEventAggregator

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** publish

**Return Type:** void

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable | string

**Constraint:**

string | <{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** channelOrInstance

**Type:** T extends [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable) ? InstanceType<T> : T

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** data

**Type:** unknown

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscribe

**Return Type:** [IDisposable](https://gitbook-18.gitbook.io/au//kernel/interfaces/interfaces/idisposable)

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable | string

**Constraint:**

string | <{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** channelOrType

**Type:** T

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Type:** [EventAggregatorCallback](https://gitbook-18.gitbook.io/au//kernel/eventaggregator/typealiases/eventaggregatorcallback)<T extends [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable) ? InstanceType<T> : T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** subscribeOnce

**Return Type:** [IDisposable](https://gitbook-18.gitbook.io/au//kernel/interfaces/interfaces/idisposable)

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable | string

**Constraint:**

string | <{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** channelOrType

**Type:** T

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Type:** [EventAggregatorCallback](https://gitbook-18.gitbook.io/au//kernel/eventaggregator/typealiases/eventaggregatorcallback)<T extends [Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable) ? InstanceType<T> : T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

