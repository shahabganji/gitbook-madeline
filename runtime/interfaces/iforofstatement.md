**Name:** IForOfStatement

**Extends:** **Name:** IExpression

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** $kind

**Type:** [ExpressionKind.ForOfStatement](https://gitbook-18.gitbook.io/au//runtime/flags/expressionkind.forofstatement)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** declaration

**Type:** [BindingIdentifierOrPattern](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/bindingidentifierorpattern)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** iterable

**Type:** [IsBindingBehavior](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isbindingbehavior)

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** count

**Return Type:** number

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** result

**Type:** ObservedCollection | number | null | undefined

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** iterate

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
**Name:** result

**Type:** ObservedCollection | number | null | undefined

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** func

**Type:** (arr: [Collection](https://gitbook-18.gitbook.io/au//runtime/observation/typealiases/collection), index: number, item: unknown) => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

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

