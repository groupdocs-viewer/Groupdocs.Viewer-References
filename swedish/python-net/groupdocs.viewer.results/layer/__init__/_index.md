---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av Layer‑klassen."
type: docs
url: /sv/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) klassen.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer.results import Layer

# Skapa ett lager med det angivna namnet.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Initierar en ny Layer-instans.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namnet på lagret. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `name` är None eller tomt. |

### Exempel

```python
from groupdocs.viewer.results import Layer

# Skapa ett lager med det angivna namnet
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Initierar en ny Layer-instans.

```python
def __init__(self, name, visible):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namnet på lagret. |
| visible | `bool` | Lagrets synlighetsindikator. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `name` är None eller tom. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Se även
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
