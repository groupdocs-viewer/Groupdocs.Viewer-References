---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de la classe Layer."
type: docs
url: /fr/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer.results import Layer

# Créez une couche avec le nom spécifié.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Initialise une nouvelle instance de Layer.

```python
def __init__(self, name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Le nom du layer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `name` est None ou vide. |

### Exemple

```python
from groupdocs.viewer.results import Layer

# Créez une couche avec le nom spécifié
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Initialise une nouvelle instance de Layer.

```python
def __init__(self, name, visible):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| name | `str` | Le nom du layer. |
| visible | `bool` | L'indicateur de visibilité du layer. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `name` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Voir aussi
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
