---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert einen Logger, der Nachrichten in eine Datei schreibt."
type: docs
url: /de/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initialisiert einen Logger, der Nachrichten in eine Datei schreibt.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Vollständiger Dateiname mit Pfad. |

### Beispiel

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

### Siehe auch
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
