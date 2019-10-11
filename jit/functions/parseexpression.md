**Name:** parseExpression

**Return Type:** TType extends [BindingType.Interpolation](https://gitbook-18.gitbook.io/au//runtime/binding/expression-parser/bindingtype.interpolation) ? [IInterpolationExpression](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iinterpolationexpression) :
TType extends [BindingType.ForCommand](https://gitbook-18.gitbook.io/au//runtime/binding/expression-parser/bindingtype.forcommand) ? [IForOfStatement](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iforofstatement) :
[IsBindingBehavior](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isbindingbehavior)

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

**Type Parameter(s):**

```**Name:**

TType

**Text:**

TType extends BindingType = BindingType.BindCommand

**Constraint:**

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
input
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
bindingType
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**TType

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

