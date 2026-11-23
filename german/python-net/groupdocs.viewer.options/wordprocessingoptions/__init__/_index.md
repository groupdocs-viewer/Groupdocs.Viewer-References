---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert Optionen für die Darstellung von Textverarbeitungsdokumenten."
type: docs
url: /de/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert Optionen für die Darstellung von Textverarbeitungsdokumenten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Rendern von nachverfolgten Änderungen aktivieren.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Siehe auch
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
