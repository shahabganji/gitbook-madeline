**Name:** h

**Return Type:** T extends keyof HTMLElementTagNameMap ? HTMLElementTagNameMap[T] : HTMLElement

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends string

**Constraint:**

string

```

```**Name:**

TChildren

**Text:**

TChildren extends H[]

**Constraint:**

[]

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
name
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**T

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
attrs
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**Record<string, string | null | undefined | string[] | boolean | number> | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
children
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**TChildren

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

