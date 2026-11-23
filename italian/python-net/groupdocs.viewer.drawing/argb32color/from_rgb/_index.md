---
title: "metodo from_rgb"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Crea un valore Argb32Color dai canali Rosso, Verde, Blu specificati, con il canale Alpha impostato a piena opacità."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Crea un valore Argb32Color dai canali Rosso, Verde, Blu specificati, con il canale Alpha impostato a piena opacità.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| red | `int` | Valore del canale rosso. |
| green | `int` | Valore del canale verde. |
| blue | `int` | Valore del canale blu. |

**Returns:** Argb32Color: New Argb32Color value.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Vedi anche
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
