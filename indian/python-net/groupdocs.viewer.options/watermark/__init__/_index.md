---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Watermark class का एक उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

[`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) क्लास का एक उदाहरण प्रारंभ करता है।

```python
def __init__(self, text):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| text | `str` | Watermark पाठ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `text` None है या खाली है। |

### उदाहरण

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

### साथ में देखें
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
