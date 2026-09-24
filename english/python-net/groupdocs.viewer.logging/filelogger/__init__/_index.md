---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a logger that writes messages to a file."
type: docs
url: /python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initializes a logger that writes messages to a file.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Full file name with path. |

### Example

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### See Also
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
