**Name:**

CollectionKindToType

**Type:**

T extends CollectionKind.array ? unknown[] :
T extends CollectionKind.indexed ? unknown[] :
T extends CollectionKind.map ? Map<unknown, unknown> :
T extends CollectionKind.set ? Set<unknown> :
T extends CollectionKind.keyed ? Set<unknown> | Map<unknown, unknown> :
never

**Initializer:**

T extends CollectionKind.array ? unknown[] :
T extends CollectionKind.indexed ? unknown[] :
T extends CollectionKind.map ? Map<unknown, unknown> :
T extends CollectionKind.set ? Set<unknown> :
T extends CollectionKind.keyed ? Set<unknown> | Map<unknown, unknown> :
never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

