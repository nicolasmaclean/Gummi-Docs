# HideIfNull(string Target)

namespace: [Gummi](../)

Inherits: `PropertyAttribute`

## Summary

Attribute that will hide the attached property if `Target` is null.

```csharp
string _foo = null;

[HideIfNull(nameof(_foo))]
public string RandomStr = "hello";
```

