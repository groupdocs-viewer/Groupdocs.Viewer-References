---
title: "for_rendering_by_height metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en CadOptions-instans för rendering efter höjd."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Initierar en CadOptions-instans för rendering efter höjd.

För kodexempel, se dokumentationen.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| height | `int` | Höjden på utdataresultatet (i pixlar). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `height` är mindre än eller lika med noll. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Se även
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
