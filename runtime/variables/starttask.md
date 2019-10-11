**Name:** StartTask

**Kind:** ✔ const

**Type:** { with<K extends >(key: K): <K>; from(task: <unknown>): ; from(promise: Promise<unknown>): ; from(promiseOrTask: ): ; }

**Initializer:**

class $StartTask implements IStartTask {
public get slot(): TaskSlot {
if (this._slot === void 0) {
throw new Error('StartTask.slot is not set');
}
return this._slot;
}
public get promiseOrTask(): PromiseOrTask {
if (this._promiseOrTask === void 0) {
throw new Error('StartTask.promiseOrTask is not set');
}
return this._promiseOrTask;
}
public get container(): IContainer {
if (this._container === void 0) {
throw new Error('StartTask.container is not set');
}
return this._container;
}
public get key(): Key {
if (this._key === void 0) {
throw new Error('StartTask.key is not set');
}
return this._key;
}
public get callback(): (instance: unknown) => PromiseOrTask {
if (this._callback === void 0) {
throw new Error('StartTask.callback is not set');
}
return this._callback;
}
public get task(): ILifecycleTask {
if (this._task === void 0) {
throw new Error('StartTask.task is not set');
}
return this._task;
}

private _slot?: TaskSlot = void 0;
private _promiseOrTask?: PromiseOrTask = void 0;
private _container?: IContainer = void 0;
private _key?: Key = void 0;
private _callback?: (instance: unknown) => PromiseOrTask = void 0;
private _task?: ILifecycleTask = void 0;

private constructor(
private readonly type: TaskType,
) {}

public static with<K extends Key>(key: K): ICallbackSlotChooser<K> {
const task = new $StartTask(TaskType.with);
task._key = key;
return task as ICallbackSlotChooser<K>;
}

public static from(task: ILifecycleTask): ISlotChooser;
public static from(promise: Promise<unknown>): ISlotChooser;
public static from(promiseOrTask: PromiseOrTask): ISlotChooser;
public static from(promiseOrTask: PromiseOrTask): ISlotChooser {
const task = new $StartTask(TaskType.from);
task._promiseOrTask = promiseOrTask;
return task;
}

public beforeCreate(): $StartTask {
return this.at(TaskSlot.beforeCreate);
}

public beforeRender(): $StartTask {
return this.at(TaskSlot.beforeRender);
}

public beforeBind(): $StartTask {
return this.at(TaskSlot.beforeBind);
}

public beforeAttach(): $StartTask {
return this.at(TaskSlot.beforeAttach);
}

public at(slot: TaskSlot): $StartTask {
this._slot = slot;
return this;
}

public call(fn: (instance: unknown) => PromiseOrTask): $StartTask {
this._callback = fn;
return this;
}

public register(container: IContainer): IContainer {
return this._container = container.register(Registration.instance(IStartTask, this));
}

public resolveTask(): ILifecycleTask {
if (this._task === void 0) {
switch (this.type) {
case TaskType.with:
this._task = new ProviderTask(this.container, this.key, this.callback);
break;
case TaskType.from:
this._task = new TerminalTask(this.promiseOrTask);
break;
}
}
return this.task;
}
} as {
with<K extends Key>(key: K): ICallbackSlotChooser<K>;
from(task: ILifecycleTask): ISlotChooser;
from(promise: Promise<unknown>): ISlotChooser;
from(promiseOrTask: PromiseOrTask): ISlotChooser;
}

