---
title: "método from_html_view_options"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase ViewInfoOptions basada en el objeto HtmlViewOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Inicializa una instancia de la clase ViewInfoOptions basada en el objeto HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `HtmlViewOptions` | Las opciones de vista HTML. |

**Returns:** A new ViewInfoOptions instance.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `options` es None. |

### Ejemplo

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Ver también
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
