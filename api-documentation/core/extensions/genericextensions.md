# GenericExtensions

namespace: [Gummi](../)

## Summary

Extension methods for the `int` type. Below is an example of how to call an extension method.

```csharp
GameObject val = new GameObject("go");
bool valIsNull = val.IsNull()
```

## Methods

`public static bool isNull<T>(this T val)`:  Returns true if `val` is null (and val is nullable).
