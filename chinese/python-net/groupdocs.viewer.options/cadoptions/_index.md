---
title: "CadOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "渲染 CAD 图纸的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

渲染 CAD 图纸的选项.

欲获取更多信息和代码示例，请参阅 Render CAD drawings and models as HTML, PDF, and image files and Specify rendering options for CAD files 文档。

CadOptions 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | 初始化一个用于按高度渲染的 CadOptions 实例。 |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | 初始化一个用于按比例因子渲染的 CadOptions 实例。 |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | 初始化一个用于按宽度渲染的 [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) 类实例。 |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | 初始化一个用于按宽度和高度渲染的 CadOptions 类实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | 图像背景颜色。 |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | 此标志启用面向性能的所有 CAD 格式转换模式，将其设置为 True 可加快转换速度，但会降低输出质量；默认值为 False，以获得最高质量。 |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | 输出结果的高度（像素）。 |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | 要渲染的 CAD 绘图图层。 |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | 要渲染的特定布局名称。布局名称区分大小写。 |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3 绘图仪配置文件。 |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | 指示是否应渲染 CAD 文档中布局的标志。 |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | 比例因子。大于 1 的值会放大输出结果；介于 0 和 1 之间的值会缩小输出结果。 |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | 要渲染的绘图区域。 |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | 输出结果的宽度（以像素为单位）。 |

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
        # 按宽度渲染并启用性能模式
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
