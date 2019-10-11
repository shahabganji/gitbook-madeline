**Name:** optional

**Kind:** ✔ const

**Type:** (key: any) => any

**Initializer:**

createResolver((key: any, handler: IContainer, requestor: IContainer) =>  {
if (requestor.has(key, true)) {
return requestor.get(key);
} else {
return null;
}
})

