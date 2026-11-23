---
title: "metodo get_attachments"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce gli allegati contenuti nel documento."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Restituisce gli allegati contenuti nel documento.

Per saperne di più:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Eccezioni | Descrizione |
| :- | :- |
| `PasswordRequiredException` | Generato quando è necessaria una password per aprire il documento. |
| `IncorrectPasswordException` | Generato quando la password specificata è errata. |

### Esempio

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Salva ogni allegato in un file
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
