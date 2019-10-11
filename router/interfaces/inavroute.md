**Name:** INavRoute

❱❱&nbsp;&nbsp;**Properties:**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** route

**Type:** [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction) | [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction)[]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** execute

**Type:** ((route: [NavRoute](https://gitbook-18.gitbook.io/au//router/nav-route/classes/navroute)) => void)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** condition

**Type:** boolean | ((route: [NavRoute](https://gitbook-18.gitbook.io/au//router/nav-route/classes/navroute)) => boolean)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** consideredActive

**Type:** [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction) | [NavigationInstruction](https://gitbook-18.gitbook.io/au//router/interfaces/typealiases/navigationinstruction)[] | ((route: [NavRoute](https://gitbook-18.gitbook.io/au//router/nav-route/classes/navroute)) => boolean)

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** compareParameters

**Type:** boolean

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** link

**Type:** string

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** title

**Type:** string

**Attributes:** ✘ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** children

**Type:** [INavRoute](https://gitbook-18.gitbook.io/au//router/nav/interfaces/inavroute)[]

**Attributes:** ✔ Optional

```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
```
**Name:** meta

**Type:** Record<string, unknown>

**Attributes:** ✔ Optional

```

