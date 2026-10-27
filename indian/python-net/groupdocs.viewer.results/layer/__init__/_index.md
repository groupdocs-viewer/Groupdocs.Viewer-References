---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Layer क्लास की नई इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

[`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer.results import Layer

# निर्दिष्ट नाम के साथ एक लेयर बनाएं।
layer = Layer("QUADRANT")
```

## __init__ {#name}

एक नया Layer उदाहरण प्रारंभ करता है।

```python
def __init__(self, name):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| name | `str` | लेयर का नाम। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `name` जब None या खाली हो तो उत्पन्न होता है। |

### उदाहरण

```python
from groupdocs.viewer.results import Layer

# निर्दिष्ट नाम के साथ एक लेयर बनाएं
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

एक नया Layer उदाहरण प्रारंभ करता है।

```python
def __init__(self, name, visible):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| name | `str` | लेयर का नाम। |
| visible | `bool` | लेयर दृश्यता संकेतक। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `name` None या खाली हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### साथ में देखें
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
