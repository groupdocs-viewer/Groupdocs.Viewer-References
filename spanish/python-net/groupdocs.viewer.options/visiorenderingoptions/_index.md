---
title: "Clase VisioRenderingOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa opciones para renderizar documentos Visio."
type: docs
url: /es/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Representa opciones para renderizar documentos Visio.

Para obtener más detalles, consulte la documentación.

El tipo VisioRenderingOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Inicializa una instancia de la clase [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | El ancho de la figura; la altura se calcula automáticamente. El valor predeterminado es 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | La propiedad renderiza solo figuras Visio, no un diagrama. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Cargar documento Visio
    with Viewer("map.vsdx") as viewer:
        # Convertir el archivo Visio a PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Renderizar solo las formas maestras.
        view_options.visio_rendering_options.render_figures_only = True
        # Especificar el ancho de la forma en píxeles.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
