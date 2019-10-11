**Name:**

ObservedCollectionKindToType

**Type:**

T extends CollectionKind.array ? IObservedArray :
T extends CollectionKind.indexed ? IObservedArray :
T extends CollectionKind.map ? IObservedMap :
T extends CollectionKind.set ? IObservedSet :
T extends CollectionKind.keyed ? IObservedSet | IObservedMap :
never

**Initializer:**

T extends CollectionKind.array ? IObservedArray :
T extends CollectionKind.indexed ? IObservedArray :
T extends CollectionKind.map ? IObservedMap :
T extends CollectionKind.set ? IObservedSet :
T extends CollectionKind.keyed ? IObservedSet | IObservedMap :
never

**Type Parameter(s):**

```**Name:**

T

**Text:**

T

```

