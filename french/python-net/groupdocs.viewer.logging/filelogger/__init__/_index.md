---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise un journal qui écrit les messages dans un fichier."
type: docs
url: /fr/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initialise un journal qui écrit les messages dans un fichier.

```python
def __init__(self, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Nom complet du fichier avec le chemin. |

### Exemple

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

### Voir aussi
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
