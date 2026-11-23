---
title: "metodo from_html_view_options"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe ViewInfoOptions basata sull'oggetto HtmlViewOptions."
type: docs
url: /it/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Inizializza un'istanza della classe ViewInfoOptions basata sull'oggetto HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `HtmlViewOptions` | Le opzioni di visualizzazione HTML. |

**Returns:** A new ViewInfoOptions instance.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `options` è None. |

### Esempio

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Vedi anche
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
