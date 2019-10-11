**Name:** ITaggedTemplateExpression

**Extends:** **Name:** IExpression

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** $kind

**Type:** [ExpressionKind.TaggedTemplate](https://gitbook-18.gitbook.io/au//runtime/flags/expressionkind.taggedtemplate)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cooked

**Type:** readonly string[] & { raw?: readonly string[] }

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** func

**Type:** [IsLeftHandSide](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/islefthandside)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** expressions

**Type:** readonly [IsAssign](https://gitbook-18.gitbook.io/au//runtime/ast/typealiases/isassign)[]

**Attributes:** ✘ Optional

```

