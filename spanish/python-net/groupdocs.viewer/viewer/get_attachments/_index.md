---
title: "método get_attachments"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve los archivos adjuntos contenidos en el documento."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Devuelve los archivos adjuntos contenidos en el documento.

Más información:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Lanza | Descripción |
| :- | :- |
| `PasswordRequiredException` | Lanzada cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | Lanzada cuando la contraseña especificada es incorrecta. |

### Ejemplo

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Guardar cada adjunto en un archivo
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ver también
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
