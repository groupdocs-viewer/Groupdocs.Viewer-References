---
title: Layer class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents a layer contained in the CAD drawing."
type: docs
url: /python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Represents a layer contained in the CAD drawing.

The Layer type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Initializes a new instance of [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) class. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Initializes a new Layer instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Initializes a new Layer instance. |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Determines whether the current Layer is the same as the specified Layer object. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Determines whether the current [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) is the same as the specified object. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Returns the hash code for the current Layer object. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Returns a string that represents the current object. |

### Properties
| Property | Description |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | The name of the layer. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | The layer visibility indicator. |

### Example

```python
from groupdocs.viewer.results import Layer

# Specify layers to render when viewing a CAD file
layers = [
    Layer("WALLS"),
    Layer("RACKS")
]
```

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
