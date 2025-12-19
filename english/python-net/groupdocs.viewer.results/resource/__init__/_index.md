---
title: Resource constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Creates new instance of [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) class.



```python
def __init__(self):
    ...
```




## __init__ {#System.String-bool}

Creates new instance of [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource) class.



```python
def __init__(self, file_name, nested):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_name | System.String | Resource file name. |
| nested | bool | Indicates whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_name` is null or empty. |





### See Also
* module [`groupdocs.viewer.results`](../../)
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource)
