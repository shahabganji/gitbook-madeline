**Name:** setup

**Return Type:** { startPromise: Promise<unknown>; ctx: ; host: Element | null; container: ; lifecycle:  & { flushCount?: number | undefined; }; testHost: HTMLDivElement; appHost: HTMLElement; au: <>; component: T & <> & { constructor: unknown; }; observerLocator: ; start: () => Promise<void>; tearDown: () => Promise<void>; }

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
template
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string | Node

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
$class
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[Constructable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/constructable)<T>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
registrations
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**any[]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
autoStart
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**boolean

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;true

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
ctx
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[HTMLTestContext](https://gitbook-18.gitbook.io/au//testing/html-test-context/classes/htmltestcontext)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TestContext.createHTMLTestContext()

