---
title: "Clase OutlookOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Contiene opciones para renderizar archivos de datos de Outlook."
type: docs
url: /es/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Contiene opciones para renderizar archivos de datos de Outlook.

Para obtener más detalles, consulte la documentación de GroupDocs.

El tipo OutlookOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | La dirección de correo electrónico utilizada para filtrar mensajes por remitente o destinatario. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | El nombre de la carpeta (p. ej., Bandeja de entrada, Elementos enviados o Elementos eliminados) a renderizar. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | El número máximo de mensajes o elementos que se pueden renderizar desde una carpeta. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Las palabras clave utilizadas para filtrar mensajes. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Limita el número de elementos renderizados por carpeta.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
