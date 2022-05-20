# Optional

namespace: [Gummi.Utility](./)

## Summary

A wrapper class for generic types. The `Enabled` field should be used instead of expensive null checks on variables. A custom `PropertyDrawer` allows `Enabled` and `Value` to be viewed/edited.

```csharp
public Optional<int> OptionalInt;

void Start()
{
    if (OptionalInt.enabled)
    {
        Debug.Log(OptionalInt.Value)
    }
}
```

## Fields

`public T Value`: The value being wrapped.

`public bool Enabled`: If this variable should be used.
