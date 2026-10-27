---
title: "IFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示所有可从所有受支持的文档格式系列（PDF、WordProcessing、Spreadsheet 和 Presentation）中提取的字体的通用接口。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

表示所有可从所有受支持的文档格式系列（PDF、WordProcessing、Spreadsheet 和 Presentation）中提取的字体的通用接口。

IFontInfo 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | 将此字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | 字体的二进制内容，以字节数组形式，如果可用；如果不可用，则为 None。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | 字体的族名称，以字符串形式。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | 此字体的格式为枚举 — TrueType、TrueType Collection、OpenType、Embedded OpenType，或 `FontFormat.unknown`。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | 字体的样式为枚举（Regular、Bold、Italic 或 Bold Italic）；某些文档格式可能仅支持 [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/)。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
