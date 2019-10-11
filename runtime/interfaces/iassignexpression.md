**Name:** IAssignExpression

**Extends:** **Name:** IExpression

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** $kind

**Type:** [ExpressionKind.Assign](https://gitbook-18.gitbook.io/au//runtime/flags/expressionkind.assign)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** target

**Type:** [IsAssignable](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isassignable)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** value

**Type:** [IsAssign](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isassign)

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

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

**Type:** [IServiceLocator](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iservicelocator)

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

