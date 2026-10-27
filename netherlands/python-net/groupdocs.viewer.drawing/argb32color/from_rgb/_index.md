---
title: "from_rgb methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Maakt een Argb32Color‑waarde aan vanuit opgegeven rood-, groen- en blauwkanalen, waarbij het Alpha‑kanaal volledig ondoorzichtig wordt ingesteld."
type: docs
url: /nl/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Maakt een Argb32Color‑waarde aan vanuit opgegeven rood-, groen- en blauwkanalen, waarbij het Alpha‑kanaal volledig ondoorzichtig wordt ingesteld.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| red | `int` | Roodkanaalwaarde. |
| green | `int` | Groenkanaalwaarde. |
| blue | `int` | Blauwkanaalwaarde. |

**Returns:** Argb32Color: New Argb32Color value.

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Zie ook
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
