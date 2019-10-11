**Name:** IChildrenObserverDescription

**Type Parameter(s):**

```**Name:**

TNode

**Text:**

TNode extends INode = INode

**Constraint:**

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** callback

**Type:** string

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** property

**Type:** string

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** options

**Type:** MutationObserverInit

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** query

**Type:** (projector: [IElementProjector](https://gitbook-18.gitbook.io/au//runtime/resources/custom-element/interfaces/ielementprojector)<TNode>) => ArrayLike<TNode>

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** filter

**Type:** (node: [INode](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inode), controller?: [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<TNode>, viewModel?: [IViewModel](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iviewmodel)<TNode>) => boolean

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** map

**Type:** (node: [INode](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inode), controller?: [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)<TNode>, viewModel?: [IViewModel](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iviewmodel)<TNode>) => any

**Attributes:** ✔ Optional

```

