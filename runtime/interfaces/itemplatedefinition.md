**Name:** ITemplateDefinition

**Extends:** **Name:** IResourceDefinition

**Type:**

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** cache

**Type:** '*' | number

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** template

**Type:** unknown

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** instructions

**Type:** [ITargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itargetedinstruction)[][]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** dependencies

**Type:** [Key](https://gitbook-18.gitbook.io/au//kernel/di/typealiases/key)[]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** build

**Type:** [IBuildInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ibuildinstruction)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** surrogates

**Type:** [ITargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itargetedinstruction)[]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** bindables

**Type:** Record<string, [IBindableDescription](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ibindabledescription)> | string[]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** childrenObservers

**Type:** Record<string, [IChildrenObserverDescription](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ichildrenobserverdescription)>

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** containerless

**Type:** boolean

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** isStrictBinding

**Type:** boolean

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** shadowOptions

**Type:** { mode: 'open' | 'closed' }

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hasSlots

**Type:** boolean

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** strategy

**Type:** [BindingStrategy](https://gitbook-18.gitbook.io/au//runtime/flags/enums/bindingstrategy)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** hooks

**Type:** Readonly<[HooksDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/classes/hooksdefinition)>

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** scopeParts

**Type:** readonly string[]

**Attributes:** ✔ Optional

```

