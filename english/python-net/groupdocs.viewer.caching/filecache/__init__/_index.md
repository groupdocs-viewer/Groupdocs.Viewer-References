---
title: FileCache constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---

## __init__ {#System.String}

Creates new instance of [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache) class.



```python
def __init__(self, cache_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cache_path | System.String | Relative or absolute path where document cache will be stored. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `cache_path` is null. |




## __init__ {#System.String-System.String}

Creates new instance of [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache) class.



```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cache_path | System.String | Relative or absolute path where document cache will be stored. |
| cache_sub_folder | System.String | The sub-folder to append to `cache_path`. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `cache_path` is null. |
| ArgumentNullException | Thrown when `cache_sub_folder` is null. |





### See Also
* module [`groupdocs.viewer.caching`](../../)
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache)
