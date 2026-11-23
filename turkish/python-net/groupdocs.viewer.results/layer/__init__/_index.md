---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Layer sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) sınıfı örneği oluşturur.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer.results import Layer

# Belirtilen adla bir katman oluştur.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Yeni bir Layer örneği oluşturur.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Katmanın adı. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `name` None veya boş olduğunda ortaya çıkar. |

### Örnek

```python
from groupdocs.viewer.results import Layer

# Belirtilen adla bir katman oluştur
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Yeni bir Layer örneği oluşturur.

```python
def __init__(self, name, visible):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Katmanın adı. |
| visible | `bool` | Katman görünürlük göstergesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `name` None veya boş olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Ayrıca Bakınız
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
