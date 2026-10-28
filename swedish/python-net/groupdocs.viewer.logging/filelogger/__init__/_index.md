---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en logger som skriver meddelanden till en fil."
type: docs
url: /sv/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initierar en logger som skriver meddelanden till en fil.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Fullständigt filnamn med sökväg. |

### Exempel

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

### Se även
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
