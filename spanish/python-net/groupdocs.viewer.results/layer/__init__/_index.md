---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de la clase Layer."
type: docs
url: /es/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer.results import Layer

# Crea una capa con el nombre especificado.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Inicializa una nueva instancia de Layer.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | El nombre de la capa. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se genera cuando `name` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer.results import Layer

# Crea una capa con el nombre especificado
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Inicializa una nueva instancia de Layer.

```python
def __init__(self, name, visible):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | El nombre de la capa. |
| visible | `bool` | El indicador de visibilidad de la capa. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `name` es None o está vacío. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Ver también
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
