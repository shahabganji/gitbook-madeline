**Name:** IExpression

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** $kind

**Type:** [ExpressionKind](https://gitbook-18.gitbook.io/au//runtime/flags/enums/expressionkind)

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** accept

**Return Type:** T

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** visitor

**Type:** [IVisitor](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/ivisitor)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** connect

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scope

**Type:** [IScope](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iscope)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** binding

**Type:** [IConnectable](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iconnectable)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** part

**Type:** string

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** evaluate

**Return Type:** unknown

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scope

**Type:** [IScope](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iscope)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** locator

**Type:** [IServiceLocator](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iservicelocator) | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** part

**Type:** string

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** assign

**Return Type:** unknown

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scope

**Type:** [IScope](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iscope)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** locator

**Type:** [IServiceLocator](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iservicelocator) | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** unknown

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** part

**Type:** string

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bind

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scope

**Type:** [IScope](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iscope)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** binding

**Type:** [IConnectable](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iconnectable)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** unbind

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scope

**Type:** [IScope](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/iscope)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** binding

**Type:** [IConnectable](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iconnectable)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

