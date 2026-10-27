---
title: "save_attachment-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Speichert die Anhangdatei in den Ziel-Stream."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Speichert die Anhangdatei in den `destination`‑Stream.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attachment | `Attachment` | Der Anhang. |
| destination | `io.RawIOBase` | Der beschreibbare Stream. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `destination` None ist. |
| `PasswordRequiredException` | Wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | Wenn das angegebene Passwort falsch ist. |
| `GroupDocsViewerException` | Wenn der Anhang nicht gefunden werden konnte. |

### Beispiel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
