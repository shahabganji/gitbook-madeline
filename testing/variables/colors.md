**Name:** colors

**Kind:** ✔ const

**Type:** Readonly<IColors>

**Initializer:**

Object_freeze(
{
bold(str: string): string {
return `\u001b[1m${str}\u001b[22m`;
},
italic(str: string): string {
return `\u001b[3m${str}\u001b[23m`;
},
underline(str: string): string {
return `\u001b[4m${str}\u001b[24m`;
},
inverse(str: string): string {
return `\u001b[7m${str}\u001b[27m`;
},
white(str: string): string {
return `\u001b[37m${str}\u001b[39m`;
},
grey(str: string): string {
return `\u001b[90m${str}\u001b[39m`;
},
black(str: string): string {
return `\u001b[30m${str}\u001b[39m`;
},
blue(str: string): string {
return `\u001b[34m${str}\u001b[39m`;
},
cyan(str: string): string {
return `\u001b[36m${str}\u001b[39m`;
},
green(str: string): string {
return `\u001b[32m${str}\u001b[39m`;
},
magenta(str: string): string {
return `\u001b[35m${str}\u001b[39m`;
},
red(str: string): string {
return `\u001b[31m${str}\u001b[39m`;
},
yellow(str: string): string {
return `\u001b[33m${str}\u001b[39m`;
},
},
)

