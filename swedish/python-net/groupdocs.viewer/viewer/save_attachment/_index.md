---
title: "save_attachment‑metoden"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Sparar bilagans fil till destinationsströmmen."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Sparar bilagefil till `destination`-ström.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attachment | `Attachment` | Bilagan. |
| destination | `io.RawIOBase` | Den skrivbara strömmen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `destination` är None. |
| `PasswordRequiredException` | När ett lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | När det angivna lösenordet är felaktigt. |
| `GroupDocsViewerException` | När bilagan inte kunde hittas. |

### Exempel

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
