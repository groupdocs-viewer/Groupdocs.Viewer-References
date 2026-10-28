---
title: "from_rgb‑metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skapar ett Argb32Color‑värde från angivna Röd-, Grön- och Blå‑kanaler, med Alfa‑kanalen satt till helt ogenomskinlig."
type: docs
url: /sv/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Skapar ett Argb32Color‑värde från angivna Röd-, Grön- och Blå‑kanaler, med Alfa‑kanalen satt till helt ogenomskinlig.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| red | `int` | Röd kanalvärde. |
| green | `int` | Grön kanalvärde. |
| blue | `int` | Blå kanalvärde. |

**Returns:** Argb32Color: New Argb32Color value.

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Se även
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
