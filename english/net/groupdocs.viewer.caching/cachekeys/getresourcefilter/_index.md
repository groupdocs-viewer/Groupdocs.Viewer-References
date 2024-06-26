---
title: GetResourceFilter
second_title: GroupDocs.Viewer for .NET API Reference
description: Returns filter string to search for cache entries that represents Resourcegroupdocs.viewer.results/resource objects.
type: docs
weight: 60
url: /net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---
## CacheKeys.GetResourceFilter method

Returns filter string to search for cache entries that represents [`Resource`](../../../groupdocs.viewer.results/resource) objects.

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | The number of page. |

### Return Value

Filter string to search for cache entries that represents [`Resource`](../../../groupdocs.viewer.results/resource) objects.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *pageNumber* is less or equal to zero. |

### See Also

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
