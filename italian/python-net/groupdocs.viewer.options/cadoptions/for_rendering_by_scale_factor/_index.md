---
title: "metodo for_rendering_by_scale_factor"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di CadOptions per il rendering per fattore di scala."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Inizializza un'istanza di CadOptions per il rendering per fattore di scala.

Per un esempio di codice, vedere la documentazione.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scale_factor | `float` | Un valore superiore a 1 ingrandisce il risultato in output; un valore compreso tra 0 e 1 riduce il risultato in output. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `scale_factor` è minore o uguale a zero. |

### Esempio

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

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
