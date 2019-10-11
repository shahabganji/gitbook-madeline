**Name:** buildTemplateDefinition

**Return Type:** TemplateDefinition

**Attributes:** ✘ Generator&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✔ Overload

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
ctor
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[CustomElementConstructor](https://gitbook-18.gitbook.io/au//runtime/definitions/typealiases/customelementconstructor) | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
nameOrDef
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string | [ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition) | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
template
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**unknown | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
cache
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**number | '*' | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
build
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[IBuildInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ibuildinstruction) | boolean | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
bindables
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**Record<string, [IBindableDescription](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ibindabledescription)> | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
instructions
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**readonly (readonly [ITargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itargetedinstruction)[])[] | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
dependencies
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**readonly [IRegistry](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/iregistry)[] | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
surrogates
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**readonly [ITargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itargetedinstruction)[] | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
containerless
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**boolean | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
shadowOptions
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**{ mode: 'open' | 'closed' } | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
hasSlots
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**boolean | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
strategy
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[BindingStrategy](https://gitbook-18.gitbook.io/au//runtime/flags/enums/bindingstrategy) | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
childrenObservers
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**Record<string, [IChildrenObserverDescription](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/ichildrenobserverdescription)> | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
aliases
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**readonly string[] | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
isStrictBinding
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**boolean | null

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

