---
title: "SpreadsheetFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "封装从已加载到 Viewer 实例的电子表格文档中获取的字体的元信息和二进制数据。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

封装从电子表格文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。电子表格文档无法嵌入字体，因此由 [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) 返回的字体会安装在运行查看器的操作系统上。

SpreadsheetFontInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | 将字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | 此字体的字符集。 |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | 此字体的颜色。 |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | 此字体的内容，以字节数组形式。如果仅有此字体的元信息而没有二进制内容，则该属性返回 None。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | 字体的族名称，不包含样式，永不为 null 或空字符串。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | 此字体的格式。 |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | 该字体具有单一的删除线。 |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | 该字体带有下划线。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | 此字体的样式——可能是 Regular、Bold、Italic 或 Bold Italic。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
