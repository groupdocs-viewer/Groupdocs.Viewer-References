---
title: "save_attachment-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Slaat bijlagebestand op naar de bestemmingsstroom."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Slaat bijlagebestand op naar `destination`-stream.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attachment | `Attachment` | De bijlage. |
| destination | `io.RawIOBase` | De beschrijfbare stream. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `destination` None is. |
| `PasswordRequiredException` | Wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | Wanneer het opgegeven wachtwoord onjuist is. |
| `GroupDocsViewerException` | Wanneer de bijlage niet gevonden kon worden. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
