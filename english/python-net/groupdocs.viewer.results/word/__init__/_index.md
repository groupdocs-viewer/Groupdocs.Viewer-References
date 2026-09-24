---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of Word."
type: docs
url: /python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Initializes a new instance of [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| word | `str` | The word. |
| x | `float` | The X coordinate of the highest left point on the page layout where the rectangle that contains word begins. |
| y | `float` | The Y coordinate of the highest left point on the page layout where the rectangle that contains word begins. |
| width | `float` | The width of the rectangle which contains the word. |
| height | `float` | The height of the rectangle which contains the word. |
| characters | `List[Character]` | The characters contained by the word. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `characters` is null. |

### See Also
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
