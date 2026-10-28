---
title: "Clase ViewInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa información de vista para un documento genérico."
type: docs
url: /es/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Representa información de vista para un documento genérico.

El tipo ViewInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Inicializa una nueva instancia de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Inicializa una nueva instancia de ViewInfo. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | El tipo del archivo. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La lista de páginas a visualizar. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
