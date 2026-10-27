---
title: "for_rendering_by_width methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de CadOptions-klasse voor renderen op breedte."
type: docs
url: /nl/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Initialiseert een instantie van de [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) klasse voor weergave op basis van breedte.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | `int` | De breedte van het uitvoerresultaat (in pixels). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `width` kleiner dan of gelijk aan nul is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Laad CAD‑bestand
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

### Zie ook
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
