---
title: "for_rendering_by_width 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 CadOptions 类的实例以按宽度渲染。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

初始化一个用于按宽度渲染的 [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) 类实例。

```python
def for_rendering_by_width(cls, width):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | `int` | 输出结果的宽度（以像素为单位）。 |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `width` 小于或等于零。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # 加载 CAD 文件
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
