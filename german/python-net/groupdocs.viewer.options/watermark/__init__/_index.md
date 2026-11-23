---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Watermark-Klasse."
type: docs
url: /de/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Initialisiert eine Instanz der [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) Klasse.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Wasserzeichentext. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `text` None oder leer ist. |

### Beispiel

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

### Siehe auch
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
