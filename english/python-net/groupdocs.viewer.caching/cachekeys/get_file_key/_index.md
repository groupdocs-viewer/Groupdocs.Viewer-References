---
title: get_file_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns unique identifier for the cache entry that represents file."
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Returns unique identifier for the cache entry that represents file.

```python
def get_file_key(cls, extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extension | `str` | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Raises | Description |
| :- | :- |
| `ValueError` | If `extension` is None or empty. |

### See Also
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
