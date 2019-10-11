**Name:**

DebounceableBinding

**Type:**

[IBinding](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/ibinding) & {
debouncedMethod: ((newValue: unknown, oldValue: unknown, flags: [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags)) => void) & { originalName: string };
debounceState: {
callContextToDebounce: [LifecycleFlags](https://gitbook-18.gitbook.io/au//runtime/flags/enums/lifecycleflags);
delay: number;
timeoutId: number;
oldValue: unknown;
};
}

**Initializer:**

IBinding & {
debouncedMethod: ((newValue: unknown, oldValue: unknown, flags: LifecycleFlags) => void) & { originalName: string };
debounceState: {
callContextToDebounce: LifecycleFlags;
delay: number;
timeoutId: number;
oldValue: unknown;
};
}

