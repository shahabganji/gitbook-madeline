**Name:** ILifecycle

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** FPS

**Type:** number

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** nextFrame

**Type:** Promise<number>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** minFPS

**Type:** number

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** maxFPS

**Type:** number

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isFlushingRAF

**Type:** boolean

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** batch

**Type:** [IAutoProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iautoprocessingqueue)<[IBatchable](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/ibatchable)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** mount

**Type:** [IProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** unmount

**Type:** [IProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bound

**Type:** [IAutoProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iautoprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** unbound

**Type:** [IAutoProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iautoprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** attached

**Type:** [IAutoProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iautoprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** detached

**Type:** [IAutoProcessingQueue](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/iautoprocessingqueue)<[IController](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/icontroller)>

**Attributes:** ✘ Optional

```

❱❱&nbsp;&nbsp;**Method(s):**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** enqueueRAF

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cb

**Type:** (flags: [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)) => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** unknown

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** priority

**Type:** [Priority](https://gitbook-18.gitbook.io/au//runtime/lifecycle/enums/priority)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** once

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** enqueueRAF

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cb

**Type:** () => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** unknown

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** priority

**Type:** [Priority](https://gitbook-18.gitbook.io/au//runtime/lifecycle/enums/priority)

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** once

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dequeueRAF

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cb

**Type:** (flags: [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)) => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** unknown

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dequeueRAF

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cb

**Type:** () => void

**Attributes:** ✘ Optional✘ Rest✘ Parameter Property

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** context

**Type:** unknown

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** processRAFQueue

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
**Name:** timestamp

**Type:** number

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** startTicking

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** stopTicking

**Return Type:** void

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** enableTimeslicing

**Return Type:** void

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** adaptive

**Type:** boolean

**Attributes:** ✔ Optional✘ Rest✘ Parameter Property

```

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** disableTimeslicing

**Return Type:** void

```

