---
title: "Clase FileName"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El nombre de archivo."
type: docs
url: /es/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

El nombre de archivo.

El tipo FileName expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Inicializa una instancia de la clase [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Campos
| Campo | Descripción |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | El nombre de archivo vacío. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | El nombre del archivo fuente. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
