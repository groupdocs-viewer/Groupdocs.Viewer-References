---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the LoadOptions class."
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes an instance of the [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) class.

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Initializes a new LoadOptions instance.

For code example, see the documentation.

```python
def __init__(self, file_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | The type of the file to open. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `file_type` is None. |

### Example

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### See Also
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
