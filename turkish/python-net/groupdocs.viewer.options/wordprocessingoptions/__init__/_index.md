---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Kelime işleme belgelerini render etmek için seçenekleri başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Kelime işleme belgelerini render etmek için seçenekleri başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # İzlenen değişikliklerin işlenmesini etkinleştir.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Ayrıca Bakınız
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
