---
title: "PresentationFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示从已加载到 Viewer 实例的演示文稿文档中获取的字体的元信息和二进制数据。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

表示从 Presentation 文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。该字体用于文档内容，可能嵌入在文档中或安装在运行查看器的操作系统上。

PresentationFontInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | 将此字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | 此字体的内容，以字节数组形式。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | 字体的族名称，不含样式；永不为 None 或空字符串。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | 此字体的格式。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | 该属性指示字体是嵌入在文档中并加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中（`True`），还是系统字体（`False`）。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | 字体的样式——可能是 Regular、Bold、Italic 或 Bold Italic。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
