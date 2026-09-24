---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of ViewInfo."
type: docs
url: /python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Initializes a new ViewInfo instance.

```python
def __init__(self, file_type, pages):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `pages` is None. |

### See Also
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
