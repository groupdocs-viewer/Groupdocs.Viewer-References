---
title: get_resource_filter method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns a filter string to search for cache entries that represent Resource objects."
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Returns a filter string to search for cache entries that represent [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) objects.

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of page. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Raises | Description |
| :- | :- |
| `ValueError` | When `page_number` is less or equal to zero. |

### See Also
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
