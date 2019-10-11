**Name:** IRouter

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isNavigating

**Type:** boolean

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** activeComponents

**Type:** [ViewportInstruction](https://gitbook-18.gitbook.io/au//router/viewport-instruction/classes/viewportinstruction)[]

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** container

**Type:** [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instructionResolver

**Type:** [InstructionResolver](https://gitbook-18.gitbook.io/au//router/instruction-resolver/classes/instructionresolver)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** navigator

**Type:** [Navigator](https://gitbook-18.gitbook.io/au//router/navigator/classes/navigator)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** navigation

**Type:** [BrowserNavigator](https://gitbook-18.gitbook.io/au//router/browser-navigator/classes/browsernavigator)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** guardian

**Type:** [Guardian](https://gitbook-18.gitbook.io/au//router/guardian/classes/guardian)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** navs

**Type:** Readonly<Record<string, [Nav](https://gitbook-18.gitbook.io/au//router/nav/classes/nav)>>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** options

**Type:** [IRouterOptions](https://gitbook-18.gitbook.io/au//router/router/interfaces/irouteroptions)

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** statefulHistory

**Type:** boolean

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** activate

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** options

**Type:** [IRouterOptions](https://gitbook-18.gitbook.io/au//router/router/interfaces/irouteroptions)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** loadUrl

**Return Type:** Promise<void>

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** deactivate

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** linkCallback

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** info

**Type:** [AnchorEventInfo](https://gitbook-18.gitbook.io/au//router/link-handler/interfaces/anchoreventinfo)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** processNavigations

**Return Type:** Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** qInstruction

**Type:** [QueueItem](https://gitbook-18.gitbook.io/au//router/queue/interfaces/queueitem)<[INavigatorInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/interfaces/inavigatorinstruction)>

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** getViewport

**Return Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport) | null

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
**Name:** connectViewport

**Return Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** element

**Type:** Element

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
**Name:** options

**Type:** [IViewportOptions](https://gitbook-18.gitbook.io/au//router/viewport/interfaces/iviewportoptions)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** disconnectViewport

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** viewport

**Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport)

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** element

**Type:** Element | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** [IRenderContext](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/irendercontext) | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** allViewports

**Return Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport)[]

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** includeDisabled

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** findScope

**Return Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** element

**Type:** Element | null

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** goto

**Return Type:** Promise<void>

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instructions

**Type:** [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction) | [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction)[]

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** options

**Type:** [IGotoOptions](https://gitbook-18.gitbook.io/au//router/router/interfaces/igotooptions)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** refresh

**Return Type:** Promise<void>

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** back

**Return Type:** Promise<void>

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** forward

**Return Type:** Promise<void>

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** setNav

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** routes

**Type:** [INavRoute](https://gitbook-18.gitbook.io/au//router/nav/interfaces/inavroute)[]

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** classes

**Type:** [INavClasses](https://gitbook-18.gitbook.io/au//router/resources/nav/interfaces/inavclasses)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** addNav

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** routes

**Type:** [INavRoute](https://gitbook-18.gitbook.io/au//router/nav/interfaces/inavroute)[]

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** classes

**Type:** [INavClasses](https://gitbook-18.gitbook.io/au//router/resources/nav/interfaces/inavclasses)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** updateNav

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** name

**Type:** string

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** findNav

**Return Type:** [Nav](https://gitbook-18.gitbook.io/au//router/nav/classes/nav)

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
**Name:** closestViewport

**Return Type:** [Viewport](https://gitbook-18.gitbook.io/au//router/viewport/classes/viewport) | null

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** element

**Type:** Element

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

```

