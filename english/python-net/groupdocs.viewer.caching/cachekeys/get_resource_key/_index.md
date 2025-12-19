---
title: get_resource_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 80
---

## get_resource_key {#int-groupdocs.viewer.results.Resource}

Returns unique identifier for the cache entry that represents [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) object.


### Returns 


Unique identifier for the cache entry that represents [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) object.


```python
def get_resource_key(self, page_number, resource):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The number of the page. |
| resource | groupdocs.viewer.results.Resource | The HTML resource. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `page_number` is less or equal to zero. |
| ArgumentNullException | Thrown when `resource` is null. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys)
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource)
