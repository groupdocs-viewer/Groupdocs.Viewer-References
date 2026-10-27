---
title: "VisioRenderingOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示用于渲染 Visio 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

表示用于渲染 Visio 文档的选项。

有关详细信息，请参阅文档。

VisioRenderingOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | 初始化 [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) 类的实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | 图形宽度；高度会自动计算。默认值为 100。 |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | 此属性仅渲染 Visio 图形，而不是整个图表。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # 加载 Visio 文档
    with Viewer("map.vsdx") as viewer:
        # 将 Visio 文件转换为 PDF。
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # 仅渲染母版形状。
        view_options.visio_rendering_options.render_figures_only = True
        # 指定形状宽度（像素）。
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
