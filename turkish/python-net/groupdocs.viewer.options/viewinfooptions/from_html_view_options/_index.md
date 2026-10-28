---
title: "from_html_view_options yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "HtmlViewOptions nesnesine dayanarak bir ViewInfoOptions sınıfının örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

HtmlViewOptions nesnesine dayanarak bir ViewInfoOptions sınıfının örneğini başlatır.

```python
def from_html_view_options(cls, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML görüntü seçenekleri. |

**Returns:** A new ViewInfoOptions instance.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `options` None ise. |

### Örnek

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Ayrıca Bakınız
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
