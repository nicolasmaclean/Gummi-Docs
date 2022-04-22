# EnableIf(string Target, object Benchmark)

namespace: [Gummi](../)

Inherits: [`VisibleBaseAttribute`](visiblebaseattribute.md)``

## Summary

Enables editing the attached property if `Target's` value is equal to `Benchmark`.

```csharp
string _foo = "foo";

[EnableIf(nameof(_foo), "foo")]
public string RandomStr = "hello";
```

See [VisibleBaseAttribute](visiblebaseattribute.md) for information about Benchmark.
