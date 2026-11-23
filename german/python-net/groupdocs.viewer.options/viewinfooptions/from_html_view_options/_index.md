---
title: "from_html_view_options Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der ViewInfoOptions-Klasse basierend auf dem HtmlViewOptions-Objekt."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Initialisiert eine Instanz der ViewInfoOptions-Klasse basierend auf dem HtmlViewOptions-Objekt.

```python
def from_html_view_options(cls, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `HtmlViewOptions` | Die HTML‑Ansichtsoptionen. |

**Returns:** A new ViewInfoOptions instance.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `options` None ist. |

### Beispiel

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Siehe auch
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
