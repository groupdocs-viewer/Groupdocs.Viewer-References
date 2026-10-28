---
title: "Método get_view_info"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve información específica de la vista y del documento."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Devuelve información específica de la vista y del documento.

Obtenga más información sobre el documento: tipo de archivo, número de páginas y otras propiedades específicas del formato:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `ViewInfoOptions` | Las opciones de información de vista. |

**Returns:** Information about view and document specific information.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `options` es None. |
| `PasswordRequiredException` | Cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | Cuando la contraseña especificada es incorrecta. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Ver también
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
