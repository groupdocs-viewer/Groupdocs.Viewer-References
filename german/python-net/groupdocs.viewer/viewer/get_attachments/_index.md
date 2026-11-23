---
title: "get_attachments-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt die im Dokument enthaltenen Anhänge zurück."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Gibt die im Dokument enthaltenen Anhänge zurück.

Mehr erfahren:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Ausnahmen | Beschreibung |
| :- | :- |
| `PasswordRequiredException` | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | Wird ausgelöst, wenn das angegebene Passwort falsch ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Jeden Anhang in einer Datei speichern
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
