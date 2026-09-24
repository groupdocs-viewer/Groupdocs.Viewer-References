---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new Resource instance."
type: docs
url: /python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new Resource instance.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Initializes a new Resource instance.

```python
def __init__(self, file_name, nested):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Resource file name. |
| nested | `bool` | Indicates whether resource resides inside another resource, e.g. font resource that resides in CSS or SVG resource. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `file_name` is None or empty. |

### See Also
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
