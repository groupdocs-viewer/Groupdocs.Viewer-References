---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance Attachment."
type: docs
url: /fr/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Initialise une nouvelle instance Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Nom de fichier de la pièce jointe. |
| file_path | `str` | Chemin relatif de la pièce jointe, p. ex. \"folder/file.docx\" ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message e‑mail ou un fichier de données. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_path` est None ou vide. |

## __init__ {#id-file_name-file_path-size}

Initialise une nouvelle instance de la classe Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| id | `str` | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |
| file_name | `str` | Nom de fichier de la pièce jointe. |
| file_path | `str` | Chemin relatif de la pièce jointe, p. ex. `folder/file.docx` ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message e‑mail ou un fichier de données. |
| size | `int` | Taille du fichier joint en octets. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_path` est nul ou vide. |

## __init__ {#id-file_name-file_path-file_type-size}

Initialise une nouvelle instance de la classe Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| id | `str` | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |
| file_name | `str` | Nom de fichier de la pièce jointe. |
| file_path | `str` | Chemin relatif de la pièce jointe, p. ex. `folder/file.docx` ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message e‑mail ou un fichier de données. |
| file_type | `FileType` | Type de fichier joint. |
| size | `int` | Taille du fichier joint en octets. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `file_type` est nul. |

### Voir aussi
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
