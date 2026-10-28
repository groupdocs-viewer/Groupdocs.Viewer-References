---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Watermark sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Bir [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) sınıfının bir örneğini başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Filigran metni. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `text` None veya boş ise. |

### Örnek

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

### Ayrıca Bakınız
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
