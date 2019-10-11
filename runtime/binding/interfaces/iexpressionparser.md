**Name:** IExpressionParser

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cache

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expressions

**Type:** Record<string, [AnyBindingExpression](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/anybindingexpression)>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parse

**Return Type:** [IForOfStatement](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iforofstatement)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expression

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bindingType

**Type:** [BindingType.ForCommand](https://gitbook-18.gitbook.io/au//runtime/binding/expression-parser/bindingtype.forcommand)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parse

**Return Type:** [IInterpolationExpression](https://gitbook-18.gitbook.io/au//runtime/ast/interfaces/iinterpolationexpression)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expression

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bindingType

**Type:** [BindingType.Interpolation](https://gitbook-18.gitbook.io/au//runtime/binding/expression-parser/bindingtype.interpolation)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parse

**Return Type:** [IsBindingBehavior](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isbindingbehavior)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expression

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bindingType

**Type:** Exclude<BindingType, BindingType.ForCommand | BindingType.Interpolation>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parse

**Return Type:** [AnyBindingExpression](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/anybindingexpression)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expression

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bindingType

**Type:** [BindingType](https://gitbook-18.gitbook.io/au//runtime/binding/expression-parser/enums/bindingtype)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

