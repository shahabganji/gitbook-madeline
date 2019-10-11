**Name:** camelCase

**Kind:** ✔ const

**Type:** (input: string) => string

**Initializer:**

(function () {
const cache = Object.create(null) as Record<string, string | undefined>;

function callback(char: string, sep: boolean): string {
return sep ? char.toUpperCase() : char.toLowerCase();
}

return function (input: string): string {
let output = cache[input];
if (output === void 0) {
output = cache[input] = baseCase(input, callback);
}

return output;
};
})()

