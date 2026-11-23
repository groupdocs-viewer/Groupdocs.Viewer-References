---
title: "from_html_view_options methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de ViewInfoOptions‑klasse op basis van het HtmlViewOptions‑object."
type: docs
url: /nl/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Initialiseert een instantie van de ViewInfoOptions‑klasse op basis van het HtmlViewOptions‑object.

```python
def from_html_view_options(cls, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `HtmlViewOptions` | De HTML‑weergave‑opties. |

**Returns:** A new ViewInfoOptions instance.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `options` None is. |

### Voorbeeld

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Zie ook
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
