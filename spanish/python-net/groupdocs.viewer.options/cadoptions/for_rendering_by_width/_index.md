---
title: "método for_rendering_by_width"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase CadOptions para renderizar por ancho."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Inicializa una instancia de la clase [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) para renderizar por ancho.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | `int` | El ancho del resultado de salida (en píxeles). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `width` es menor o igual a cero. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Cargar archivo CAD
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

### Ver también
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
