---
title: "Watermark 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示文本水印。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

表示文本水印。

请查看在线文档以获取更多信息。

Watermark 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | 初始化 [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) 类的实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | 水印颜色。默认值为 `Rgb24Color.known_colors.css_level1.red`。 |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | 用于水印的字体名称。 |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | 水印位置。默认值为 `Position.diagonal`。 |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | 水印大小。默认值为 [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/)。 |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | 水印文本。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # 加载文档
    with Viewer("sample.docx") as viewer:
        # 创建 HTML 文件。
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # 添加水印。
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
使用 `Watermark` 的任务指南：

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
