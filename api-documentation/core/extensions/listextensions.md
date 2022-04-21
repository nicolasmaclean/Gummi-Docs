# ListExtensions

namespace: [Gummi](../)

## Summary

Extension methods for the `IList` type.

```csharp
List<string> ls = new List<string>() {"1", "2", "3"};
print(ls.PrettyPrint())
```

## Methods

`public static string PrettyPrint(this IList list)`:  creates a pretty tostring of the list. An example may be seen below.

```
01: hello
02: world
03: :)
```

