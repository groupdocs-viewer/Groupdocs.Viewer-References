---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Layer 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) 类实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer.results import Layer

# 使用指定的名称创建图层。
layer = Layer("QUADRANT")
```

## __init__ {#name}

初始化一个新的 Layer 实例。

```python
def __init__(self, name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 层的名称。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `name` 为 None 或为空时抛出。 |

### 示例

```python
from groupdocs.viewer.results import Layer

# 使用指定的名称创建图层
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

初始化一个新的 Layer 实例。

```python
def __init__(self, name, visible):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 层的名称。 |
| visible | `bool` | 层可见性指示器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `name` 为 None 或为空时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 另见
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
