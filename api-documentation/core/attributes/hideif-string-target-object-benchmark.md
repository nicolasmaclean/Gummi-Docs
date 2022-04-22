# HideIf(string Target, object Benchmark)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)``

## Summary

Hides the attached property if `Target's` value is equal to `Benchmark`.

```csharp
string _foo = "foo";

[HideIf(nameof(_foo), "foo")]
public string RandomStr = "hello";
```

See [VisibleBaseAttribute](visiblebaseattribute.md) for information about Benchmark.
