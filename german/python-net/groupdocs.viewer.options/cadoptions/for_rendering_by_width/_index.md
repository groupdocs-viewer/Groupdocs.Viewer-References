---
title: "for_rendering_by_width Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der CadOptions-Klasse für das Rendern nach Breite."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Initialisiert eine Instanz der [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) Klasse für die Darstellung nach Breite.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | `int` | Die Breite des Ausgaberesultats (in Pixeln). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `width` kleiner oder gleich null ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD-Datei laden
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

### Siehe auch
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
