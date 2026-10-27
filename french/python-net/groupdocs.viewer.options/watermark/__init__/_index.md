---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe Watermark."
type: docs
url: /fr/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Initialise une instance de la classe [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/).

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte du filigrane. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `text` est None ou vide. |

### Exemple

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

### Voir aussi
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
