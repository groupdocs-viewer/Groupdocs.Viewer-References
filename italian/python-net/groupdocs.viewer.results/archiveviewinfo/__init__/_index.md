---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di ArchiveViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Inizializza una nuova istanza di ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| folders | `List[str]` | L'elenco delle cartelle contenute nel file di archivio. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `folders` è None. |

### Vedi anche
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
