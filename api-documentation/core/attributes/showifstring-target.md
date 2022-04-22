# ShowIfstring Target)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)

## Summary

Shows the attached property if `Target's` value is null (or if a value type, default).

```csharp
string _foo = null;

[ShowIf(nameof(_foo))]
public string RandomStr = "hello";
```
