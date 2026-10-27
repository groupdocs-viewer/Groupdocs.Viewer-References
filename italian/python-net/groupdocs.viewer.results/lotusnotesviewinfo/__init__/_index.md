---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di LotusNotesViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Inizializza una nuova istanza della classe [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| notes_count | `int` | Il conteggio delle note contenuto nel file di archiviazione del database Lotus. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `notes_count` è None. |

### Vedi anche
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
