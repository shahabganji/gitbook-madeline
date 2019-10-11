**Name:**

IIndexable

**Type:**

{ [K in TKey]: TValue } & TBase

**Initializer:**

{ [K in TKey]: TValue } & TBase

**Type Parameter(s):**

```**Name:**

TBase

**Text:**

TBase extends {} = {}

**Constraint:**

{}

```

```**Name:**

TValue

**Text:**

TValue = unknown

```

```**Name:**

TKey

**Text:**

TKey extends PropertyKey = Exclude<PropertyKey, keyof TBase>

**Constraint:**

string | number | symbol

```

