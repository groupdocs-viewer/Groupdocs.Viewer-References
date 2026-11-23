---
title: "ViewOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "渲染选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewoptions/
is_root: false
weight: 340
---


## ViewOptions class

渲染选项.

ViewOptions 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/#page_number-rotation) | 对页面应用顺时针旋转。 |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | 页面旋转。 |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | 要应用于每页的文本水印。 |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | 存档文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | CAD 绘图视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | 在渲染期间缺少所需字体时用于文档的默认字体。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | 电子邮件消息视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | 邮件存储数据文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Microsoft Outlook 数据文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | PDF 文档视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | 演示文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | 项目管理文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | 当属性设置为 True 时禁用渲染注释。默认情况下为 False，因此会显示所有注释。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | 属性启用或禁用渲染注释。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | 属性启用隐藏页面的渲染。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | 属性启用对某些格式的笔记和注释的渲染。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | 电子表格文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | 渲染文本文件的文本选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Visio 文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Web 文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | 文字处理文件视图选项。 (继承自 [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("sample.pptx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.render_notes = True
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
