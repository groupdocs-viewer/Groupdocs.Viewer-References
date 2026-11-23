---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza della classe Layer."
type: docs
url: /it/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer.results import Layer

# Crea un layer con il nome specificato.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Inizializza una nuova istanza di Layer.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Il nome del layer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `name` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer.results import Layer

# Crea un layer con il nome specificato
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Inizializza una nuova istanza di Layer.

```python
def __init__(self, name, visible):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Il nome del layer. |
| visible | `bool` | L'indicatore di visibilità del layer. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `name` è None o vuoto. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Vedi anche
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
