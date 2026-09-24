---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of Line."
type: docs
url: /python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Initializes a new instance of the [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) class.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| line | `str` | The line. |
| x | `float` | The X coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| y | `float` | The Y coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| width | `float` | The width of the rectangle which contains the line (in pixels). |
| height | `float` | The height of the rectangle which contains the line (in pixels). |
| words | `List[Word]` | The words contained by the line. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `line` is null or empty, or when `words` is null. |

### See Also
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
