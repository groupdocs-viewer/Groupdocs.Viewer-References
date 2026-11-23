---
title: "Clase ArchiveOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Contiene opciones para renderizar los archivos de archivo."
type: docs
url: /es/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Contiene opciones para renderizar los archivos de archivo.

El tipo ArchiveOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Inicializa una instancia de la clase [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | El nombre del archivo de archivo mostrado. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | La carpeta a renderizar. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
