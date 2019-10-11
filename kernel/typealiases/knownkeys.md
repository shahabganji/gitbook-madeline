**Name:**

KnownKeys

**Type:**

{
[K in keyof T]: string extends K ? never : number extends K ? never : K
} extends {[_ in keyof T]: infer U} ? U : never

**Initializer:**

{
[K in keyof T]: string extends K ? never : number extends K ? never : K
} extends {[_ in keyof T]: infer U} ? U : never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

