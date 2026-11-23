---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi opsi untuk merender dokumen pengolah kata."
type: docs
url: /id/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi opsi untuk merender dokumen pengolah kata.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Aktifkan perenderan perubahan yang dilacak.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Lihat Juga
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
