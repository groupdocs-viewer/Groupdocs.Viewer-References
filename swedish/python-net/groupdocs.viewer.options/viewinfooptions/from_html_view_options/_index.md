---
title: "from_html_view_options metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av ViewInfoOptions-klassen baserat på HtmlViewOptions-objektet."
type: docs
url: /sv/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Initierar en instans av ViewInfoOptions-klassen baserat på HtmlViewOptions-objektet.

```python
def from_html_view_options(cls, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML‑vyalternativen. |

**Returns:** A new ViewInfoOptions instance.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `options` är None. |

### Exempel

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Se även
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
