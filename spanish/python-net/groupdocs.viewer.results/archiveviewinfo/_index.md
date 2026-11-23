---
title: "Clase ArchiveViewInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa información de vista para un archivo de archivo."
type: docs
url: /es/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Representa información de vista para un archivo de archivo.

El tipo ArchiveViewInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Inicializa una nueva instancia de [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Inicializa una nueva instancia de ArchiveViewInfo. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Devuelve una cadena que representa el objeto actual. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Las carpetas contenidas en el archivo. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | El tipo del archivo. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La lista de páginas a visualizar. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ejemplo

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Guías de tareas que usan `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
