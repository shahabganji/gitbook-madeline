**Name:** AuDOMTest

**Type:** { setup(): { au: <>; container: ; lifecycle: ; host: ; }; createTextDefinition(expression: string, name?: string): ; createTemplateControllerDefinition(instruction: , name?: string): ; createElementDefinition(instructions: [][], name: string): ; createIfInstruction(expression: string, def: ): ; createElseInstruction(def: ): ; createRepeatInstruction(expression: string, def: ): ; createReplaceableInstruction(def: ): ; createWithInstruction(expression: string, def: ): ; createElementInstruction(name: string, bindings: [string, string][], parts?: Record<string, > | undefined): ; createLetInstruction(bindings: [string, string][], toBindingContext?: boolean): ; }

**Attribute:** ✘ Array Literal

**Element(s):**

**Attribute:** ✔ Object Literal

**Method(s):**

**Name:**

setup

**Attributes:** ✘ Generator

**ReturnType:**

{ au: [Aurelia](https://gitbook-18.gitbook.io/au//runtime/aurelia/classes/aurelia); container: [IContainer](https://gitbook-18.gitbook.io/au//kernel/di/interfaces/icontainer); lifecycle: [ILifecycle](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/ilifecycle); host: [AuNode](https://gitbook-18.gitbook.io/au//testing/au-dom/classes/aunode) }

**Name:**

createTextDefinition

**Attributes:** ✘ Generator

**ReturnType:**

[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
expression
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
name
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`${expression}-text`

**Name:**

createTemplateControllerDefinition

**Attributes:** ✘ Generator

**ReturnType:**

[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
instruction
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
name
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;instruction.res

**Name:**

createElementDefinition

**Attributes:** ✘ Generator

**ReturnType:**

[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
instructions
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[TargetedInstruction](https://gitbook-18.gitbook.io/au//runtime/definitions/typealiases/targetedinstruction)[][]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
name
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createIfInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
expression
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
def
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createElseInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
def
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createRepeatInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
expression
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
def
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createReplaceableInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
def
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createWithInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateTemplateController](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydratetemplatecontroller)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
expression
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
def
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createElementInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[HydrateElementInstruction](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/hydrateelementinstruction)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
name
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**string

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
bindings
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[string, string][]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
parts
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**Record<string, [ITemplateDefinition](https://gitbook-18.gitbook.io/au//runtime/definitions/interfaces/itemplatedefinition)>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

**Name:**

createLetInstruction

**Attributes:** ✘ Generator

**ReturnType:**

[LetElementInstruction](https://gitbook-18.gitbook.io/au//runtime/instructions/classes/letelementinstruction)

❱❱&nbsp;&nbsp;**Parameters:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
bindings
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**[string, string][]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✘ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
toBindingContext
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**boolean

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Attributes:**✔ Optional&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Rest&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;✘ Parameter Property

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Initializer:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;false

