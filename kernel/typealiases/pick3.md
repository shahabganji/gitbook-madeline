**Name:**

Pick3

**Type:**

{
[P1 in K1]: { [P2 in K2]: { [P3 in K3]: ((T[K1])[K2])[P3] } }
}

**Initializer:**

{
[P1 in K1]: { [P2 in K2]: { [P3 in K3]: ((T[K1])[K2])[P3] } }
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

```**Name:**

K3

**Text:**

K3 extends keyof T[K1][K2]

**Constraint:**

keyof T[K1][K2]

```

