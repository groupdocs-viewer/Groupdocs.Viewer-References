---
title: "Layer 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 CAD 绘图中包含的图层。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

表示 CAD 绘图中包含的图层。

Layer 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | 初始化一个新的 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) 类实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | 初始化一个新的 Layer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | 初始化一个新的 Layer 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | 确定当前 Layer 是否与指定的 Layer 对象相同。 |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | 检查当前 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) 是否等于指定的对象。 |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | 返回当前 Layer 对象的哈希码。 |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | 返回表示当前对象的字符串。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | 层的名称。 |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | 层可见性指示器。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 另见
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
