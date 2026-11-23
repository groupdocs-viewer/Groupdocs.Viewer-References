---
title: "for_rendering_by_width metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av CadOptions-klassen för rendering efter bredd."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Initierar en instans av klassen [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) för rendering efter bredd.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | `int` | Bredden på utdataresultatet (i pixlar). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `width` är mindre än eller lika med noll. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Läs in CAD-fil
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Se även
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
