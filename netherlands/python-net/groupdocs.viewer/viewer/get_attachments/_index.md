---
title: "get_attachments-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert bijlagen die in het document zijn opgenomen."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Retourneert bijlagen die in het document zijn opgenomen.

Meer informatie:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Gooit | Beschrijving |
| :- | :- |
| `PasswordRequiredException` | Wordt gegooid wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | Wordt gegooid wanneer het opgegeven wachtwoord onjuist is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Sla elke bijlage op in een bestand
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
