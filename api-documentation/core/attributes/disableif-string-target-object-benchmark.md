# DisableIf(string Target, object Benchmark)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)``

## Summary

Disables editing the attached property if `Target's` value is equal to `Benchmark`.

```csharp
string _foo = "foo";

[DisableIf(nameof(_foo), "foo")]
public string RandomStr = "hello";
```

See [VisibleBaseAttribute](visiblebaseattribute.md) for information about Benchmark.
