---
title: "Clase OutlookViewInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa información de vista para un archivo de datos de Outlook."
type: docs
url: /es/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Representa información de vista para un archivo de datos de Outlook.

El tipo OutlookViewInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Inicializa una nueva instancia de [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Inicializa una nueva instancia de OutlookViewInfo. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Devuelve una cadena que representa el objeto actual. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | La lista de carpetas contenidas en el archivo de datos de Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | El tipo del archivo. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La lista de páginas a visualizar. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ejemplo

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
Guías de tareas que usan `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
