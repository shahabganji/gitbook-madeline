**Name:** IResourceType

**Extends:** **Name:** ConstructableClass<TProto, unknown>

**Type:** { new (...args: any[]): TProto & { constructor: unknown; }; readonly prototype: TProto & { constructor: unknown; }; }

, **Name:** IRegistry

**Type:**

**Type Parameter(s):**

```**Name:**

TDef

**Text:**

TDef

```

```**Name:**

TProto

**Text:**

TProto

```

```**Name:**

TClass

**Text:**

TClass extends ConstructableClass<TProto, unknown> = ConstructableClass<TProto>

**Constraint:**

{ new (...args: any[]): TProto & { constructor: unknown; }; readonly prototype: TProto & { constructor: unknown; }; }

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** kind

**Type:** [IResourceKind](https://gitbook-18.gitbook.io/au//kernel/resource/interfaces/iresourcekind)<TDef, TProto, TClass>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** description

**Type:** ResourceDescription<TDef>

**Attributes:** ✘ Optional

```

