---
title: "for_rendering_by_scale_factor Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine CadOptions-Instanz für die Darstellung nach Skalierungsfaktor."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Initialisiert eine CadOptions-Instanz für die Darstellung nach Skalierungsfaktor.

Für ein Code‑Beispiel siehe die Dokumentation.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_factor | `float` | Ein Wert größer als 1 vergrößert das Ausgabeergebnis; ein Wert zwischen 0 und 1 verkleinert das Ausgabeergebnis. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `scale_factor` kleiner oder gleich null ist. |

### Beispiel

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

### Siehe auch
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
