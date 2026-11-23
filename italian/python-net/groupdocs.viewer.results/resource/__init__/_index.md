---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di Resource."
type: docs
url: /it/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di Resource.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Inizializza una nuova istanza di Resource.

```python
def __init__(self, file_name, nested):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Nome file della risorsa. |
| nested | `bool` | Indica se la risorsa si trova all'interno di un'altra risorsa, ad es. risorsa di carattere che si trova in una risorsa CSS o SVG. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `file_name` è None o vuoto. |

### Vedi anche
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
