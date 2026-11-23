---
title: "from_rgb 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "从指定的红、绿、蓝通道创建 Argb32Color 值，并将 Alpha 通道设置为完全不透明。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

从指定的红、绿、蓝通道创建 Argb32Color 值，并将 Alpha 通道设置为完全不透明。

```python
def from_rgb(cls, red, green, blue):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| red | `int` | 红色通道值。 |
| green | `int` | 绿色通道值。 |
| blue | `int` | 蓝色通道值。 |

**Returns:** Argb32Color: New Argb32Color value.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### 另见
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
