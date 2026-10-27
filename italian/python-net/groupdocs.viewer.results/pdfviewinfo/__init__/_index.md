---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di PdfViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di PdfViewInfo.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Inizializza una nuova istanza di PdfViewInfo.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| printing_allowed | `bool` | L'indicatore di autorizzazione di stampa. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `pages` è None. |

### Vedi anche
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
