---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa opciones para renderizar documentos de procesamiento de texto."
type: docs
url: /es/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa opciones para renderizar documentos de procesamiento de texto.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Habilitar la renderización de cambios rastreados.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Ver también
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
