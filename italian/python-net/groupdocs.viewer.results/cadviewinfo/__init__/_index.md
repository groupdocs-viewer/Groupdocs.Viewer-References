---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di CadViewInfo."
type: docs
url: /it/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Inizializza una nuova istanza di CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file. |
| pages | `List[Page]` | L'elenco delle pagine da visualizzare. |
| layers | `List[Layer]` | L'elenco dei layer contenuti nel disegno CAD. |
| layouts | `List[Layout]` | L'elenco dei layer contenuti nel disegno CAD. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `layouts` è None. |

### Vedi anche
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
