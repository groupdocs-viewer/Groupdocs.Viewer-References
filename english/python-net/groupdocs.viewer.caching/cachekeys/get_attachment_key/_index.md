---
title: get_attachment_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns unique identifier for the cache entry that represents attachment file."
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Returns unique identifier for the cache entry that represents attachment file.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| attachment_id | `str` | Unique (in context of single file) identifier of the attachment. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Raises | Description |
| :- | :- |
| `ValueError` | Thrown when `attachment_id` is null or empty. |

### See Also
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
