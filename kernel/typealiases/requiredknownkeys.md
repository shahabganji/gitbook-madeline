**Name:**

RequiredKnownKeys

**Type:**

{
[K in keyof T]: {} extends Pick<T, K> ? never : K
} extends { [_ in keyof T]: infer U } ? ({} extends U ? never : U) : never

**Initializer:**

{
[K in keyof T]: {} extends Pick<T, K> ? never : K
} extends { [_ in keyof T]: infer U } ? ({} extends U ? never : U) : never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

