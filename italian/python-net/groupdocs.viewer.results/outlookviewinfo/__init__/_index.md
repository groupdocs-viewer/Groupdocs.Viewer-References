---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di OutlookViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Inizializza una nuova istanza di OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| folders | `List[str]` | L'elenco delle cartelle contenute nel file Outlook Data. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `folders` è None. |

### Vedi anche
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
