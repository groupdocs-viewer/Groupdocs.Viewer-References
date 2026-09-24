---
title: get_page_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns unique identifier for the cache entry that represents page file."
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Returns unique identifier for the cache entry that represents page file.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of the page. |
| extension | `str` | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Raises | Description |
| :- | :- |
| `ValueError` | When `extension` is None or empty. |

### See Also
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
