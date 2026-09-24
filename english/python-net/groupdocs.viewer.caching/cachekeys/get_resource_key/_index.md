---
title: get_resource_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns unique identifier for the cache entry that represents Resource object."
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Returns unique identifier for the cache entry that represents [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) object.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of the page. |
| resource | `Resource` | The HTML resource. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Raises | Description |
| :- | :- |
| `ValueError` | If `page_number` is less than or equal to zero, or if `resource` is None. |

### See Also
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
