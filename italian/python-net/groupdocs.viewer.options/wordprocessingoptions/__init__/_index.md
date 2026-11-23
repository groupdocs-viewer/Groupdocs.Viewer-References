---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza le opzioni per il rendering dei documenti di elaborazione testi."
type: docs
url: /it/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza le opzioni per il rendering dei documenti di elaborazione testi.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Abilita il rendering delle modifiche tracciate.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Vedi anche
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
