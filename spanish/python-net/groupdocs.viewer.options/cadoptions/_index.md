---
title: "Clase CadOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Las opciones para renderizar dibujos CAD."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Las opciones para renderizar dibujos CAD.

Para obtener más información y ejemplos de código, consulte la documentación Render CAD drawings and models as HTML, PDF, and image files y Specify rendering options for CAD files.

El tipo CadOptions expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Inicializa una instancia de CadOptions para renderizar por altura. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Inicializa una instancia de CadOptions para renderizar por factor de escala. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Inicializa una instancia de la clase [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) para renderizar por ancho. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Inicializa una instancia de la clase CadOptions para renderizar por ancho y altura. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | El color de fondo de la imagen. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | La bandera que habilita un modo de conversión orientado al rendimiento para todos los formatos CAD, donde establecerla en True acelera la conversión a costa de una calidad de salida reducida; por defecto es False para máxima calidad. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | La altura del resultado de salida (en píxeles). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Las capas de dibujo CAD a renderizar. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | El nombre del diseño específico a renderizar. El nombre del diseño distingue entre mayúsculas y minúsculas. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | El archivo de configuración del plotter PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | La bandera que indica si se deben renderizar los diseños del documento CAD. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | El factor de escala. Un valor mayor que 1 agranda el resultado de salida; un valor entre 0 y 1 reduce el resultado de salida. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Las regiones de dibujo a renderizar. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | El ancho del resultado de salida (en píxeles). |

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
        # Renderizar por ancho y habilitar el modo de rendimiento
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
