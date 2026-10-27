---
title: "Metodo save_attachment"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Salva il file allegato nello stream di destinazione."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Salva il file allegato nello stream `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attachment | `Attachment` | L'allegato. |
| destination | `io.RawIOBase` | Il flusso scrivibile. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `destination` è None. |
| `PasswordRequiredException` | Quando è richiesta una password per aprire il documento. |
| `IncorrectPasswordException` | Quando la password specificata è errata. |
| `GroupDocsViewerException` | Quando l'allegato non è stato trovato. |

### Esempio

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
