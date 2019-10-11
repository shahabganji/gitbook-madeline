**Name:** ISVGAnalyzer

**Kind:** ✔ const

**Type:** <>

**Initializer:**

DI.createInterface<ISVGAnalyzer>('ISVGAnalyzer').withDefault(x => x.singleton(class {
public isStandardSvgAttribute(node: INode, attributeName: string): boolean {
return false;
}
}))

