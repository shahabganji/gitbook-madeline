**Name:** trimFull

**Kind:** ✔ const

**Type:** (input: string) => string

**Initializer:**

(function () {
const cache: Record<string, string | undefined> = {};

return function (input: string) {
let result = cache[input];
if (result === void 0) {
result = '';
const length = input.length;
let ch = 0;

for (let i = 0; i < length; ++i) {
ch = input.charCodeAt(i);
if (ch > 0x20) {
result += String.fromCharCode(ch);
}
}

cache[input] = result;
}

return result;
};
}())

