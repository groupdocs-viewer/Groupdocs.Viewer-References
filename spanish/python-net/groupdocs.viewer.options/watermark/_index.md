---
title: "Clase Watermark"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa una marca de agua de texto."
type: docs
url: /es/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Representa una marca de agua de texto.

Consulte la documentación en línea para obtener más información.

El tipo Watermark expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Inicializa una instancia de la clase [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | El color de la marca de agua. El valor predeterminado es `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | El nombre de la fuente utilizada para la marca de agua. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | La posición de la marca de agua. El valor predeterminado es `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | El tamaño de la marca de agua. El valor predeterminado es [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | El texto de la marca de agua. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Cargar documento
    with Viewer("sample.docx") as viewer:
        # Crear un archivo HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Agregar marca de agua.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Guías de tareas que usan `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
