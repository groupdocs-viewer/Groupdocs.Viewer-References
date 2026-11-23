---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di Word."
type: docs
url: /it/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Inizializza una nuova istanza di [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| word | `str` | La parola. |
| x | `float` | La coordinata X del punto più alto a sinistra nel layout della pagina dove inizia il rettangolo che contiene la parola. |
| y | `float` | La coordinata Y del punto più alto a sinistra nel layout della pagina dove inizia il rettangolo che contiene la parola. |
| width | `float` | La larghezza del rettangolo che contiene la parola. |
| height | `float` | L'altezza del rettangolo che contiene la parola. |
| characters | `List[Character]` | I caratteri contenuti nella parola. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `characters` è null. |

### Vedi anche
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
