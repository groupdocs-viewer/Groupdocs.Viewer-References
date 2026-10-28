---
title: "método from_rgb"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Crea un valor Argb32Color a partir de los canales Rojo, Verde y Azul especificados, con el canal Alfa configurado como completamente opaco."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Crea un valor Argb32Color a partir de los canales Rojo, Verde y Azul especificados, con el canal Alfa configurado como completamente opaco.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| red | `int` | Valor del canal rojo. |
| green | `int` | Valor del canal verde. |
| blue | `int` | Valor del canal azul. |

**Returns:** Argb32Color: New Argb32Color value.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Ver también
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
