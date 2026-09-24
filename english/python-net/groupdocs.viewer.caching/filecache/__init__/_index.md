---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new FileCache instance."
type: docs
url: /python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Initializes a new FileCache instance.

```python
def __init__(self, cache_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cache_path | `str` | Relative or absolute path where document cache will be stored. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `cache_path` is None. |

## __init__ {#cache_path-cache_sub_folder}

Initializes a new instance of the FileCache class.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cache_path | `str` | Relative or absolute path where document cache will be stored. |
| cache_sub_folder | `str` | The sub-folder to append to `cache_path`. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `cache_sub_folder` is None. |

### See Also
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
