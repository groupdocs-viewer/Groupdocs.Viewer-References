---
title: "Método save_attachment"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Guarda el archivo adjunto en el flujo de destino."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Guarda el archivo adjunto en el flujo `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attachment | `Attachment` | El adjunto. |
| destination | `io.RawIOBase` | El flujo de escritura. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `destination` es None. |
| `PasswordRequiredException` | Cuando se requiere una contraseña para abrir el documento. |
| `IncorrectPasswordException` | Cuando la contraseña especificada es incorrecta. |
| `GroupDocsViewerException` | Cuando no se pudo encontrar el adjunto. |

### Ejemplo

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Ver también
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
