**Name:** ISanitizer

**Kind:** ✔ const

**Type:** <>

**Initializer:**

DI.createInterface<ISanitizer>('ISanitizer').withDefault(x => x.singleton(class {
public sanitize(input: string): string {
return input.replace(SCRIPT_REGEX, '');
}
}))

