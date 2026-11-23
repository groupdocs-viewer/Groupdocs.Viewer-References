---
title: "EmailOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "包含渲染电子邮件的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

包含渲染电子邮件的选项.

GroupDocs.Viewer 支持 EmailOptions 类，允许您为渲染电子邮件消息指定不同的选项。要访问这些选项，请根据所需的输出格式，在以下视图选项类之一上使用 EmailOptions 属性：

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

EmailOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | 初始化 [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/) 类的实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | 时间格式（可以包含时区）。如果未设置，则使用当前系统格式。 |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | 电子邮件消息 [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) 与字段文本表示之间的映射。 |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | 输出页面的尺寸。 |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | 消息的时区偏移量。 |

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
