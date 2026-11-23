---
title: "for_rendering_by_height methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een CadOptions‑instantie voor weergave op basis van hoogte."
type: docs
url: /nl/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Initialiseert een CadOptions‑instantie voor weergave op basis van hoogte.

Voor een codevoorbeeld, zie de documentatie.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| height | `int` | De hoogte van het uitvoerresultaat (in pixels). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `height` kleiner dan of gelijk aan nul is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Zie ook
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
