---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di Line."
type: docs
url: /it/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Inizializza una nuova istanza della classe [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| line | `str` | La linea. |
| x | `float` | La coordinata X del punto più alto a sinistra nel layout della pagina dove inizia il rettangolo che contiene la linea. |
| y | `float` | La coordinata Y del punto più alto a sinistra nel layout della pagina dove inizia il rettangolo che contiene la linea. |
| width | `float` | La larghezza del rettangolo che contiene la linea (in pixel). |
| height | `float` | L'altezza del rettangolo che contiene la linea (in pixel). |
| words | `List[Word]` | Le parole contenute nella linea. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `line` è null o vuoto, o quando `words` è null. |

### Vedi anche
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
