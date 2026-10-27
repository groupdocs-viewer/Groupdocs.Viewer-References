---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di ProjectManagementViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Inizializza una nuova istanza di ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| start_date | `datetime` | La data e ora da cui il progetto è iniziato. |
| end_date | `datetime` | La data e ora in cui il progetto deve essere completato. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `pages` è None. |

### Vedi anche
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
