---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100.

Untuk detail dan contoh kode, lihat https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ dan turunannya.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Lihat Juga
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
