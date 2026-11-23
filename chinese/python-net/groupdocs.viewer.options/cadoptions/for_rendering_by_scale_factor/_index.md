---
title: "for_rendering_by_scale_factor 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个用于按比例因子渲染的 CadOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

初始化一个用于按比例因子渲染的 CadOptions 实例。

代码示例请参见文档。

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_factor | `float` | 值大于 1 会放大输出结果；值在 0 与 1 之间会缩小输出结果。 |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `scale_factor` 小于或等于零时引发。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
