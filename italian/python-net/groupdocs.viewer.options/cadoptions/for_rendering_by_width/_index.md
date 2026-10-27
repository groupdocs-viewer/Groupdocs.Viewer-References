---
title: "metodo for_rendering_by_width"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe CadOptions per il rendering in base alla larghezza."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Inizializza un'istanza della classe [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) per il rendering per larghezza.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | `int` | La larghezza del risultato in output (in pixel). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `width` è minore o uguale a zero. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Carica file CAD
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

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
