---
title: FileName class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The filename."
type: docs
url: /python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

The filename.

The FileName type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Initializes an instance of the [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) class. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Returns a string that represents the current object. |

### Fields
| Field | Description |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | The empty filename. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | The name of the source file. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
