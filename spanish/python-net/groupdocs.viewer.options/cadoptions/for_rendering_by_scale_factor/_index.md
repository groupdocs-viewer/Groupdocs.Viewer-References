---
title: "método for_rendering_by_scale_factor"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de CadOptions para renderizar por factor de escala."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Inicializa una instancia de CadOptions para renderizar por factor de escala.

Para un ejemplo de código, consulte la documentación.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_factor | `float` | Un valor mayor que 1 amplía el resultado de salida; un valor entre 0 y 1 reduce el resultado de salida. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se genera cuando `scale_factor` es menor o igual a cero. |

### Ejemplo

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

### Ver también
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
