---
title: get_file_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 50
---

## get_file_key {#System.String}

Returns unique identifier for the cache entry that represents file.


### Returns 


Unique identifier for the cache entry that represents file.


```python
def get_file_key(self, extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| extension | System.String | The filename suffix (including the period ".") e.g. ".doc". |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `extension` is null or empty. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys)
