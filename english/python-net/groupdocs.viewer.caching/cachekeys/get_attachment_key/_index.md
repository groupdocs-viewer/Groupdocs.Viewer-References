---
title: get_attachment_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 20
---

## get_attachment_key {#System.String}

Returns unique identifier for the cache entry that represents attachment file.


### Returns 


Unique identifier for the cache entry that represents attachment file.


```python
def get_attachment_key(self, attachment_id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| attachment_id | System.String | Unique (in context of single file) identifier of the attachment. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `attachment_id` is null or empty. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys)
