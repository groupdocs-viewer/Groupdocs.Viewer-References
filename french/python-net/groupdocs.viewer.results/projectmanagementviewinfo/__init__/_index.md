---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de ProjectManagementViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Initialise une nouvelle instance de ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| start_date | `datetime` | La date et l'heure à partir desquelles le projet a commencé. |
| end_date | `datetime` | La date et l'heure auxquelles le projet doit être terminé. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `pages` est None. |

### Voir aussi
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
