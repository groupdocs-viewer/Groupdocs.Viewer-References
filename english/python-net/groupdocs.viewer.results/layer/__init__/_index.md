---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of the Layer class."
type: docs
url: /python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) class.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer.results import Layer

# Create a layer with the specified name.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Initializes a new Layer instance.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The name of the layer. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `name` is None or empty. |

### Example

```python
from groupdocs.viewer.results import Layer

# Create a layer with the specified name
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Initializes a new Layer instance.

```python
def __init__(self, name, visible):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The name of the layer. |
| visible | `bool` | The layer visibility indicator. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `name` is None or empty. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### See Also
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
