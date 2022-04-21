# HideIfNotNull(string Target)

namespace: [Gummi](../)

Inherits: `PropertyAttribute`

## Summary

Attribute that will hide the attached property if `Target` is not null.

```csharp
string _foo = null;

[HideIfNotNull(nameof(_foo))]
public string RandomStr = "hello";
```

