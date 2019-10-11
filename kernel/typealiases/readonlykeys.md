**Name:**

ReadonlyKeys

**Type:**

{
[P in keyof T]-?: [IfEquals](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/ifequals)<{ [Q in P]: T[P] }, { -readonly [Q in P]: T[P] }, never, P>
}[keyof T]

**Initializer:**

{
[P in keyof T]-?: IfEquals<{ [Q in P]: T[P] }, { -readonly [Q in P]: T[P] }, never, P>
}[keyof T]

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

