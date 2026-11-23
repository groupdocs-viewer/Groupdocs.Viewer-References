---
title: "método for_rendering_by_height"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de CadOptions para renderizar por altura."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Inicializa una instancia de CadOptions para renderizar por altura.

Para un ejemplo de código, consulte la documentación.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| height | `int` | La altura del resultado de salida (en píxeles). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `height` es menor o igual a cero. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Ver también
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
