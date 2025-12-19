---
title: get_page_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 60
---

## get_page_key {#int-System.String}

Returns unique identifier for the cache entry that represents page file.


### Returns 


Unique identifier for the cache entry that represents page file.


```python
def get_page_key(self, page_number, extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The number of the page. |
| extension | System.String | The filename suffix (including the period ".") e.g. ".doc". |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `page_number` is less or equal to zero. |
| ArgumentException | Thrown when `extension` is null or empty. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys)
