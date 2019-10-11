**Name:**

CollectionTypeToKind

**Type:**

T extends unknown[] ? CollectionKind.array | CollectionKind.indexed :
T extends Set<unknown> ? CollectionKind.set | CollectionKind.keyed :
T extends Map<unknown, unknown> ? CollectionKind.map | CollectionKind.keyed :
never

**Initializer:**

T extends unknown[] ? CollectionKind.array | CollectionKind.indexed :
T extends Set<unknown> ? CollectionKind.set | CollectionKind.keyed :
T extends Map<unknown, unknown> ? CollectionKind.map | CollectionKind.keyed :
never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

