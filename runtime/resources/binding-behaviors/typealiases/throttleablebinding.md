**Name:**

ThrottleableBinding

**Type:**

[IBinding](https://gitbook-18.gitbook.io/au//runtime/lifecycle/interfaces/ibinding) & {
throttledMethod: ((value: unknown) => unknown) & { originalName: string };
throttleState: {
delay: number;
timeoutId: number;
last: number;
newValue?: unknown;
};
}

**Initializer:**

IBinding & {
throttledMethod: ((value: unknown) => unknown) & { originalName: string };
throttleState: {
delay: number;
timeoutId: number;
last: number;
newValue?: unknown;
};
}

