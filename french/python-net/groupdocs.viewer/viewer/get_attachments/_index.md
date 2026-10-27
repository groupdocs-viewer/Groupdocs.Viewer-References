---
title: "méthode get_attachments"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie les pièces jointes contenues dans le document."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Renvoie les pièces jointes contenues dans le document.

En savoir plus:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Exceptions | Description |
| :- | :- |
| `PasswordRequiredException` | Lancée lorsque le mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | Lancée lorsque le mot de passe spécifié est incorrect. |

### Exemple

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Enregistrer chaque pièce jointe dans un fichier
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
