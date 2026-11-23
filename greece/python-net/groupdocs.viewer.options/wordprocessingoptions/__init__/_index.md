---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί τις επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου."
type: docs
url: /el/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί τις επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Ενεργοποίηση απόδοσης των παρακολουθούμενων αλλαγών.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Δείτε επίσης
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
