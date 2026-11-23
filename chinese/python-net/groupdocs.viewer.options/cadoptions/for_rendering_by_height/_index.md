---
title: "for_rendering_by_height 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个用于按高度渲染的 CadOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

初始化一个用于按高度渲染的 CadOptions 实例。

代码示例请参见文档。

```python
def for_rendering_by_height(cls, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| height | `int` | 输出结果的高度（像素）。 |

**Returns:** CadOptions: New instance configured for rendering by height.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `height` 小于或等于零时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
