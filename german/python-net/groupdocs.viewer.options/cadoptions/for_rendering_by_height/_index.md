---
title: "for_rendering_by_height Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine CadOptions-Instanz für die Darstellung nach Höhe."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Initialisiert eine CadOptions-Instanz für die Darstellung nach Höhe.

Für ein Code‑Beispiel siehe die Dokumentation.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| height | `int` | Die Höhe des Ausgabeergebnisses (in Pixeln). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `height` kleiner oder gleich null ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Siehe auch
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
