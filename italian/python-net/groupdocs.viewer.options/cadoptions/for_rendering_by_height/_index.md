---
title: "metodo for_rendering_by_height"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di CadOptions per il rendering per altezza."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Inizializza un'istanza di CadOptions per il rendering per altezza.

Per un esempio di codice, vedere la documentazione.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| height | `int` | L'altezza del risultato in output (in pixel). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `height` è minore o uguale a zero. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
