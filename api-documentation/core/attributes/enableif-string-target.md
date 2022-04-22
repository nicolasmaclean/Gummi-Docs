# EnableIf(string Target)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)``

## Summary

Enables editing the attached property if `Target's` value is null (or if a value type, default).

```csharp
string _foo = null;

[EnableIf(nameof(_foo))]
public string RandomStr = "hello";
```
