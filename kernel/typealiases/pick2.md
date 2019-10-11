**Name:**

Pick2

**Type:**

{
[P1 in K1]: { [P2 in K2]: (T[K1])[P2] }
}

**Initializer:**

{
[P1 in K1]: { [P2 in K2]: (T[K1])[P2] }
}

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

```**Name:**

K1

**Text:**

K1 extends keyof T

**Constraint:**

keyof T

```

```**Name:**

K2

**Text:**

K2 extends keyof T[K1]

**Constraint:**

keyof T[K1]

```

