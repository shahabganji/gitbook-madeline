**Name:** IRenderer

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instructionRenderers

**Type:** Record<string, IInstructionRenderer['render']>

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** render

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** flags

**Type:** [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dom

**Type:** [IDOM](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/idom)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** [IRenderContext](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/irendercontext)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** renderable

**Type:** [IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** targets

**Type:** ArrayLike<[INode](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inode)>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** templateDefinition

**Type:** TemplateDefinition

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** host

**Type:** [INode](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inode)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parts

**Type:** TemplatePartDefinitions

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

