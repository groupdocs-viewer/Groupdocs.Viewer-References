---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar alternativ för rendering av ordbehandlingsdokument."
type: docs
url: /sv/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar alternativ för rendering av ordbehandlingsdokument.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Aktivera rendering av spårade ändringar.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Se även
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
