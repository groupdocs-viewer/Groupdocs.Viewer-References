---
title: "PdfOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示渲染为 PDF 文档的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

表示渲染为 PDF 文档的选项.

有关详细信息，请参阅文档。

PdfOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | 初始化 PdfOptions 类的新实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | 此属性在页面渲染期间禁用符号分组，以实现精确的符号定位。 |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | 此属性在渲染为 HTML 时禁用内容复制保护。 |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | 此属性禁用当前 XPS/OXPS 文档中所有字体的任何许可证限制。 |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | 此属性启用字体微调。 |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | 此属性在渲染为 HTML 时，按原始 PDF 文档的 Z 顺序渲染文本和图形。 |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | 固定布局选项使 PDF 和 EPUB 文档以固定布局渲染为 HTML。 |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | 渲染为 HTML 时图像资源的输出图像质量。默认质量为 `ImageQuality.LOW`。 |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | 输出页面尺寸设置为匹配源 PDF 文档的页面尺寸。 |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | 此选项可在 HTML 输出中将 PDF 文件中的文本渲染为图像。 |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | 此属性可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # 在将 PDF 页面渲染为图像时启用字体微调。
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
