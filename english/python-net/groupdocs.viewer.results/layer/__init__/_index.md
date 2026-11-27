---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of Layer class."
type: docs
url: /python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) class.

```python
def __init__(self):
    ...
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
| `ValueError` | When `name` is null or empty. |

### Example

```python
from groupdocs.viewer.results import Layer

# Create a layer named "WALLS"
layer = Layer("WALLS")
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
| `ValueError` | If `name` is None or empty. |

### Example

```python
from groupdocs.viewer.results import Layer

# Render specific layers in a CAD drawing
layers = [
    Layer("WALLS"),
    Layer("RACKS", visible=True)
]
```

### See Also
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
