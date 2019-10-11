**Name:**

ObserversLookup

**Type:**

[IIndexable](https://gitbook-18.gitbook.io/au//kernel/interfaces/typealiases/iindexable)<{
getOrCreate(
lifecycle: [ILifecycle](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/ilifecycle),
flags: [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags),
obj: [IBindingContext](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/ibindingcontext) | [IOverrideContext](https://gitbook-18.gitbook.io/au//runtime/observation/interfaces/ioverridecontext),
key: string,
): PropertyObserver;
}, PropertyObserver>

**Initializer:**

IIndexable<{
getOrCreate(
lifecycle: ILifecycle,
flags: LifecycleFlags,
obj: IBindingContext | IOverrideContext,
key: string,
): PropertyObserver;
}, PropertyObserver>

