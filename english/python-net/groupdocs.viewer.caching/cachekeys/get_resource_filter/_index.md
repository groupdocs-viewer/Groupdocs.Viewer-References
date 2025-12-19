---
title: get_resource_filter method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 70
---

## get_resource_filter {#int}

Returns filter string to search for cache entries that represents [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) objects.


### Returns 


Filter string to search for cache entries that represents [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) objects.


```python
def get_resource_filter(self, page_number):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The number of page. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `page_number` is less or equal to zero. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys)
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource)
