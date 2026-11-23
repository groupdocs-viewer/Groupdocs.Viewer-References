---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de ArchiveViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initialise une nouvelle instance d'ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| folders | `List[str]` | La liste des dossiers contenus dans le fichier d'archive. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `folders` est None. |

### Voir aussi
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
