---
title: "for_rendering_by_scale_factor methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een CadOptions‑instantie voor weergave op basis van schaalfactor."
type: docs
url: /nl/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initialiseert een CadOptions‑instantie voor weergave op basis van schaalfactor.

Voor een codevoorbeeld, zie de documentatie.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scale_factor | `float` | Een waarde hoger dan 1 vergroot het uitvoerresultaat; een waarde tussen 0 en 1 verkleint het uitvoerresultaat. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `scale_factor` kleiner dan of gelijk aan nul is. |

### Voorbeeld

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

### Zie ook
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
