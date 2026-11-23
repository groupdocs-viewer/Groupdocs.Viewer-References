---
title: "méthode from_html_view_options"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe ViewInfoOptions basée sur l'objet HtmlViewOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Initialise une instance de la classe ViewInfoOptions basée sur l'objet HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `HtmlViewOptions` | Les options de vue HTML. |

**Returns:** A new ViewInfoOptions instance.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `options` est None. |

### Exemple

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Voir aussi
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
