---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de OutlookViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initialise une nouvelle instance OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| folders | `List[str]` | La liste des dossiers contenus dans le fichier de données Outlook. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lancée lorsque `folders` est None. |

### Voir aussi
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
