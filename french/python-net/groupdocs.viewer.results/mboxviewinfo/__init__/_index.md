---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de MboxViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Initialise une nouvelle instance de [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| notes_count | `int` | Le nombre de notes contenu dans le fichier de stockage de base de données Lotus. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `notes_count` est None. |

### Voir aussi
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
