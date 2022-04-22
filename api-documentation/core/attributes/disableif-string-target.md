# DisableIf(string Target)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)``

## Summary

Disables editing the attached property if `Target's` value is null (or if a value type, default).

```csharp
string _foo = null;

[DisableIf(nameof(_foo))]
public string RandomStr = "hello";
```
