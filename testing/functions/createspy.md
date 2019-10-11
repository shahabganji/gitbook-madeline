**Name:** createSpy

**Return Type:** AnyFunction

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends {} | AnyFunction = VoidFunction

**Constraint:**

{} | AnyFunction

```

```**Name:**

K

**Text:**

K extends keyof T | never = never

**Constraint:**

keyof T

```

```**Name:**

F

**Text:**

F extends AnyFunction | never = never

**Constraint:**

AnyFunction

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
instanceOrInnerFn
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**T

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
key
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**K

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
callThroughOrInnerFn
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**true | F

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

