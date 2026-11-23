---
title: "get_attachments‑metoden"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar bilagor som finns i dokumentet."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Returnerar bilagor som finns i dokumentet.

Läs mer:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Uppstår | Beskrivning |
| :- | :- |
| `PasswordRequiredException` | Kastas när ett lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | Kastas när det angivna lösenordet är felaktigt. |

### Exempel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Spara varje bilaga till en fil
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
