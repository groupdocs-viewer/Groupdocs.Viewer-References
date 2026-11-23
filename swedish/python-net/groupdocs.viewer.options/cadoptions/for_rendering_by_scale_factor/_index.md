---
title: "for_rendering_by_scale_factor metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en CadOptions-instans för rendering efter skalningsfaktor."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initierar en CadOptions-instans för rendering efter skalningsfaktor.

För kodexempel, se dokumentationen.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_factor | `float` | Värde högre än 1 förstorar utdataresultatet; värde mellan 0 och 1 minskar utdataresultatet. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `scale_factor` är mindre än eller lika med noll. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### Se även
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
