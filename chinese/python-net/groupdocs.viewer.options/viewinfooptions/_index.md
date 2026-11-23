---
title: "ViewInfoOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "用于检索视图信息的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/
is_root: false
weight: 330
---


## ViewInfoOptions class

用于检索视图信息的选项.

ViewInfoOptions 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/) | 初始化一个 ViewInfoOptions 实例，以在渲染为 HTML 时检索视图信息。 |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#render_single_page) | 初始化一个 ViewInfoOptions 实例，以在渲染为 HTML 时检索视图信息。 |
| [for_html_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view_boolean/) |  |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/) | 初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 实例，以在渲染为 JPG 时检索视图信息。 |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#extract_text) | 初始化一个 ViewInfoOptions 实例，以在渲染为 JPG 时检索视图信息。 |
| [for_jpg_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view_boolean/) |  |
| [for_pdf_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/) | 初始化一个 ViewInfoOptions 实例，以在渲染为 PDF 时检索视图信息。 |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/) | 初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 类的实例，以在渲染为 PNG 时检索视图信息。 |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#extract_text) | 初始化一个 ViewInfoOptions 类的实例，以在渲染为 PNG 时检索视图信息。 |
| [for_png_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view_boolean/) |  |
| [from_html_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/#options) | 基于 HtmlViewOptions 对象初始化一个 ViewInfoOptions 类的实例。 |
| [from_jpg_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/#options) | 基于提供的 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 初始化一个 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 实例。 |
| [from_pdf_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_pdf_view_options/#options) | 从 PdfViewOptions 对象初始化一个 ViewInfoOptions 实例。 |
| [from_png_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_png_view_options/#options) | 从 PngViewOptions 对象初始化一个 ViewInfoOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/extract_text/) | 此属性启用文本提取。 |
| [height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/height/) | 输出图像的高度（像素，仅用于渲染为 PNG/JPG）。 |
| [max_height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_height/) | 输出图像的最大高度（像素，仅用于渲染为 PNG/JPG）。 |
| [max_width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_width/) | 输出图像的最大宽度（像素，仅用于渲染为 PNG/JPG）。 |
| [width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/width/) | 输出图像的宽度（像素，仅用于渲染为 PNG/JPG）。 |
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
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Guides
使用 `ViewInfoOptions` 的任务指南：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
