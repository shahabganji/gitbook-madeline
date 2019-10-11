**Name:** IViewLocator

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getViewComponentForObject

**Return Type:** ComposableObjectComponentType<T> | null

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends ClassInstance<ComposableObject>

**Constraint:**

<Pick<<>, "created" | "binding" | "bound" | "unbinding" | "unbound" | "attaching" | "attached" | "detaching" | "detached" | "caching">>

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** object

**Type:** T | null | undefined

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** viewNameOrSelector

**Type:** string | [ViewSelector](https://gitbook-18.gitbook.io/au//runtime/templating/view/typealiases/viewselector)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

