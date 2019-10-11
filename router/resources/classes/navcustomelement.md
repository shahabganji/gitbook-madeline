**Name:** NavCustomElement

**Decorator(s):**

**Name:** inject

**Attributes:**

✔ Decorator Factory

**Parameters:**

```
IRouter
```

```
INode
```

**Name:** customElement

**Attributes:**

✔ Decorator Factory

**Parameters:**

```
{
name: 'au-nav', template:
`<template>
<nav if.bind="name" class="\${name} \${navClasses.nav}">
<au-nav routes.bind="navRoutes" classes.bind="navClasses" containerless></au-nav>
</nav>
<ul if.bind="routes" class="nav-level-\${level} \${classes.ul}">
<li repeat.for="route of routes" if.bind="route.visible" class="\${route.active ? classes.liActive : ''} \${route.hasChildren} \${classes.li}">
<a if.bind="route.link && route.link.length" href="\${route.link}" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<a if.bind="route.execute" click.trigger="route.executeAction($event)" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<span if.bind="(!route.link || !route.link.length) && !route.execute && !route.children" class="\${route.active ? classes.aActive : ''} \${classes.span} nav-separator" innerhtml.bind="route.title"></span>
<a if.bind="(!route.link || !route.link.length) && !route.execute && route.children" click.delegate="route.toggleActive()" href="" class="\${route.active ? classes.aActive : ''} \${classes.a}" innerhtml.bind="route.title"></a>
<au-nav if.bind="route.children" routes.bind="route.children" level.bind="level + 1" classes.bind="classes" containerless></au-nav>
</li>
</ul>
</template>` }
```

