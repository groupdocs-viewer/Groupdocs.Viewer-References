---
title: "Clase ProjectManagementViewInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa información de vista para un documento de MS Project."
type: docs
url: /es/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Representa información de vista para un documento de MS Project.

El tipo ProjectManagementViewInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Inicializa una nueva instancia de [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Inicializa una nueva instancia de ProjectManagementViewInfo. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Devuelve una cadena que representa el objeto actual. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | La fecha y hora en que se debe completar el proyecto. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | La fecha y hora a partir de la cual comenzó el proyecto. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | El tipo del archivo. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La lista de páginas a visualizar. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ejemplo

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
Guías de tareas que usan `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
