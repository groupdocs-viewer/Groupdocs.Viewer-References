---
title: "Clase ViewerSettings"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Define configuraciones para personalizar el comportamiento del Viewer."
type: docs
url: /es/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Define configuraciones para personalizar el comportamiento de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

El tipo ViewerSettings expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Inicializa una nueva instancia de ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Inicializa una nueva instancia de ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Inicializa una nueva instancia de ViewerSettings. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | La implementación de caché utilizada para almacenar los resultados de renderizado. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | La implementación del registrador utilizada para registrar (Errores, Advertencias, Trazas). |

### Ejemplo

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### Ver también
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
