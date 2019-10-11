**Name:**

LifecycleFlags

**Modifiers:**

export, const

**Members:**

none = 0b00000_0000000_0000000000000_00_0000

persistentBindingFlags = 0b11111_0000000_0000000000000_00_1111

allowParentScopeTraversal = 0b00001_0000000_0000000000000_00_0000

observeLeafPropertiesOnly = 0b00010_0000000_0000000000000_00_0000

targetObserverFlags = 0b01100_0000000_0000000000000_00_1111

noTargetObserverQueue = 0b00100_0000000_0000000000000_00_0000

persistentTargetObserverQueue = 0b01000_0000000_0000000000000_00_0000

secondaryExpression = 0b10000_0000000_0000000000000_00_0000

bindingStrategy = 0b00000_0000000_0000000000000_00_1111

getterSetterStrategy = 0b00000_0000000_0000000000000_00_0001

proxyStrategy = 0b00000_0000000_0000000000000_00_0010

isStrictBindingStrategy = 0b00000_0000000_0000000000000_00_0100

update = 0b00000_0000000_0000000000000_11_0000

updateTargetInstance = 0b00000_0000000_0000000000000_01_0000

updateSourceExpression = 0b00000_0000000_0000000000000_10_0000

from = 0b00000_0000000_1111111111111_00_0000

fromFlush = 0b00000_0000000_0000000001111_00_0000

fromAsyncFlush = 0b00000_0000000_0000000000001_00_0000

fromSyncFlush = 0b00000_0000000_0000000000010_00_0000

fromTick = 0b00000_0000000_0000000000100_00_0000

fromBatch = 0b00000_0000000_0000000001000_00_0000

fromStartTask = 0b00000_0000000_0000000010000_00_0000

fromStopTask = 0b00000_0000000_0000000100000_00_0000

fromBind = 0b00000_0000000_0000001000000_00_0000

fromUnbind = 0b00000_0000000_0000010000000_00_0000

fromAttach = 0b00000_0000000_0000100000000_00_0000

fromDetach = 0b00000_0000000_0001000000000_00_0000

fromCache = 0b00000_0000000_0010000000000_00_0000

fromDOMEvent = 0b00000_0000000_0100000000000_00_0000

fromLifecycleTask = 0b00000_0000000_1000000000000_00_0000

allowPublishRoundtrip = 0b00000_0000001_0000000000000_00_0000

isPublishing = 0b00000_0000010_0000000000000_00_0000

mustEvaluate = 0b00000_0000100_0000000000000_00_0000

isTraversingParentScope = 0b00000_0001000_0000000000000_00_0000

isOriginalArray = 0b00000_0010000_0000000000000_00_0000

isCollectionMutation = 0b00000_0100000_0000000000000_00_0000

reorderNodes = 0b00000_1000000_0000000000000_00_0000
