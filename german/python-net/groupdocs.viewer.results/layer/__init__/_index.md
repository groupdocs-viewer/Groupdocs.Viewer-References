---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse Layer."
type: docs
url: /de/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer.results import Layer

# Erstellt einen Layer mit dem angegebenen Namen.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Initialisiert eine neue Layer-Instanz.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Der Name des Layers. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `name` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer.results import Layer

# Erstellt einen Layer mit dem angegebenen Namen
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Initialisiert eine neue Layer-Instanz.

```python
def __init__(self, name, visible):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Der Name des Layers. |
| visible | `bool` | Der Sichtbarkeitsindikator des Layers. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `name` None oder leer ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Siehe auch
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
