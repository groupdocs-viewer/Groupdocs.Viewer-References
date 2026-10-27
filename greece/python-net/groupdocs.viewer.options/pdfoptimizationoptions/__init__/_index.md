---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100.

Για λεπτομέρειες και παραδείγματα κώδικα, δείτε https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ και τα θυγατρικά του.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Δείτε επίσης
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
