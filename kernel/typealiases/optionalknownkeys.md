**Name:**

OptionalKnownKeys

**Type:**

{
[K in keyof T]: string extends K ? never : number extends K ? never : {} extends Pick<T, K> ? K : never
} extends { [_ in keyof T]: infer U } ? ({} extends U ? never : U) : never

**Initializer:**

{
[K in keyof T]: string extends K ? never : number extends K ? never : {} extends Pick<T, K> ? K : never
} extends { [_ in keyof T]: infer U } ? ({} extends U ? never : U) : never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

