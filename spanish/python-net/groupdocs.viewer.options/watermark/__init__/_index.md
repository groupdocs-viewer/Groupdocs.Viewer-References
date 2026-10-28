---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase Watermark."
type: docs
url: /es/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Inicializa una instancia de la clase [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/).

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto de la marca de agua. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `text` es None o está vacío. |

### Ejemplo

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

### Ver también
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
