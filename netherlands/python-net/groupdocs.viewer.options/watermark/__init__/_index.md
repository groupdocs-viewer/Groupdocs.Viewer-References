---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de Watermark-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Initialiseert een instantie van de [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) klasse.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Watermerktekst. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `text` None of leeg is. |

### Voorbeeld

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

### Zie ook
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
