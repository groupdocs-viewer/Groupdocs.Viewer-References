---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de Layer-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer.results import Layer

# Maak een laag met de opgegeven naam.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Initialiseert een nieuw Layer-exemplaar.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | De naam van de laag. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `name` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer.results import Layer

# Maak een laag met de opgegeven naam
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Initialiseert een nieuw Layer-exemplaar.

```python
def __init__(self, name, visible):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | De naam van de laag. |
| visible | `bool` | De zichtbaarheidsindicator van de laag. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `name` None of leeg is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Zie ook
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
