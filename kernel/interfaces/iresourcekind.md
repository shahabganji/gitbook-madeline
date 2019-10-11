**Name:** IResourceKind

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
**Name:** name

**Type:** string

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** keyFrom

**Return Type:** string

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isType

**Return Type:** Type is T & TClass & IResourceType<TDef, TProto>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** Type

**Type:** T & Partial<[IResourceType](https://gitbook-18.gitbook.io/au//kernel/resource/interfaces/iresourcetype)<TDef, TProto>>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** define

**Return Type:** T & TClass & [IResourceType](https://gitbook-18.gitbook.io/au//kernel/resource/interfaces/iresourcetype)<TDef, TProto>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** ctor

**Type:** T

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** define

**Return Type:** T & TClass & [IResourceType](https://gitbook-18.gitbook.io/au//kernel/resource/interfaces/iresourcetype)<TDef, TProto>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** definition

**Type:** TDef

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** ctor

**Type:** T

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** define

**Return Type:** T & TClass & [IResourceType](https://gitbook-18.gitbook.io/au//kernel/resource/interfaces/iresourcetype)<TDef, TProto>

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends Constructable

**Constraint:**

<{}>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nameOrDefinition

**Type:** string | TDef

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** ctor

**Type:** T

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

