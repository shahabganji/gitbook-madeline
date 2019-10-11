**Name:** INodeSequence

**Extends:** **Name:** INode

**Type:**

**Type Parameter(s):**

```**Name:**

T

**Text:**

T extends INode = INode

**Constraint:**

```

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isMounted

**Type:** boolean

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isLinked

**Type:** boolean

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** next

**Type:** [INodeSequence](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inodesequence)<T>

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** childNodes

**Type:** ArrayLike<T>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** firstChild

**Type:** T

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** lastChild

**Type:** T

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** findTargets

**Return Type:** ArrayLike<T>

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** insertBefore

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** refNode

**Type:** T | [IRenderLocation](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/irenderlocation)<T>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** appendTo

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** parent

**Type:** T

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** remove

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addToLinked

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** unlink

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** link

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** next

**Type:** [INodeSequence](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/inodesequence)<T> | [IRenderLocation](https://gitbook-18.gitbook.io/au//runtime/dom/interfaces/irenderlocation)<T> | undefined

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

