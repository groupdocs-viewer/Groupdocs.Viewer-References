---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من الفئة Layer."
type: docs
url: /ar/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من الفئة [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer.results import Layer

# إنشاء طبقة بالاسم المحدد.
layer = Layer("QUADRANT")
```

## __init__ {#name}

ينشئ مثيلاً جديدًا من Layer.

```python
def __init__(self, name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم الطبقة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرفع عندما تكون `name` فارغة أو None. |

### مثال

```python
from groupdocs.viewer.results import Layer

# إنشاء طبقة بالاسم المحدد
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

ينشئ مثيلاً جديدًا من Layer.

```python
def __init__(self, name, visible):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| name | `str` | اسم الطبقة. |
| visible | `bool` | مؤشر رؤية الطبقة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `name` None أو فارغ. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### انظر أيضًا
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
