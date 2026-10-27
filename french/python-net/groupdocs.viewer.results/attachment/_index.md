---
title: "Classe Attachment"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente un fichier joint contenu dans un message électronique, une archive, un document PDF ou un fichier de données Outlook."
type: docs
url: /fr/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Représente un fichier joint contenu dans un message électronique, une archive, un document PDF ou un fichier de données Outlook.

Le type Attachment expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Initialise une nouvelle instance [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Initialise une nouvelle instance Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Initialise une nouvelle instance de la classe Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Initialise une nouvelle instance de la classe Attachment. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Renvoie une chaîne qui représente l'objet actuel. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Le nom de fichier de la pièce jointe. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Le chemin relatif de la pièce jointe, par ex. `folder/file.docx`, ou le nom de fichier lorsque le fichier se trouve à la racine d’une archive, dans un message e‑mail ou un fichier de données. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Le type de fichier de la pièce jointe. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | L’identifiant unique de la pièce jointe dans le contexte d’un seul fichier contenant cette pièce jointe. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | La taille du fichier de la pièce jointe en octets. |

### Exemple

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Accéder aux propriétés de la pièce jointe, p. ex., le nom de fichier
        print(attachment.file_name)
        # Enregistrer la pièce jointe à un chemin de fichier
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
