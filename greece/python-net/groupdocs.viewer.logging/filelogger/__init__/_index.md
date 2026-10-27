---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί έναν καταγραφέα που γράφει μηνύματα σε αρχείο."
type: docs
url: /el/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Αρχικοποιεί έναν καταγραφέα που γράφει μηνύματα σε αρχείο.

```python
def __init__(self, file_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | `str` | Πλήρες όνομα αρχείου με διαδρομή. |

### Παράδειγμα

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

### Δείτε επίσης
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
