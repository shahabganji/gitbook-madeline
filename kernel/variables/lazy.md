**Name:** lazy

**Kind:** ✔ const

**Type:** (key: any) => any

**Initializer:**

createResolver((key: any, handler: IContainer, requestor: IContainer) =>  {
let instance: unknown = null; // cache locally so that lazy always returns the same instance once resolved
return () => {
if (instance == null) {
instance = requestor.get(key);
}

return instance;
};
})

