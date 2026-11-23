---
title: "méthode save_attachment"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Enregistre le fichier de pièce jointe dans le flux de destination."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Enregistre le fichier joint dans le flux `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| attachment | `Attachment` | La pièce jointe. |
| destination | `io.RawIOBase` | Le flux inscriptible. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `destination` est None. |
| `PasswordRequiredException` | Lorsqu'un mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | Lorsque le mot de passe spécifié est incorrect. |
| `GroupDocsViewerException` | Lorsque la pièce jointe n'a pas pu être trouvée. |

### Exemple

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
