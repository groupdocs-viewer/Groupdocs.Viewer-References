---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe Watermark."
type: docs
url: /it/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Inizializza un'istanza della classe [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/).

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo della filigrana. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `text` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

with Viewer("sample.docx") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "add_text_watermark/output-watermark.html"
    )
    view_options.watermark = Watermark("This is a watermark")
    viewer.view(view_options)
```

### Vedi anche
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
