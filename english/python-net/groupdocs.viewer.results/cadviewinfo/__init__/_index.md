---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new CadViewInfo instance."
type: docs
url: /python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Initializes a new CadViewInfo instance.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file. |
| pages | `List[Page]` | The list of pages to view. |
| layers | `List[Layer]` | The list of layers contained by the CAD drawing. |
| layouts | `List[Layout]` | The list of layers contained by the CAD drawing. |

| Raises | Description |
| :- | :- |
| `ValueError` | Thrown when `layouts` is None. |

### See Also
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
