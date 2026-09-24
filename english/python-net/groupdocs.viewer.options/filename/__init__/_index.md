---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the FileName class."
type: docs
url: /python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initializes an instance of the [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) class.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | The name of the file. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `file_name` is None. |

### Example

```python
from groupdocs.viewer.options import FileName

# Create a FileName instance with a custom archive name
custom_name = FileName("Sample Files")
```

### See Also
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
