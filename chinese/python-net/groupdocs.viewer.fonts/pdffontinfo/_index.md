---
title: "PdfFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "封装加载到 Viewer 实例中的 PDF 字体的元数据和二进制数据，该字体可能嵌入在文档中或安装在运行 GroupDocs.Viewer 的操作系统上。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

封装加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的 PDF 字体的元数据和二进制数据，该字体可能嵌入在文档中或安装在运行 GroupDocs.Viewer 的操作系统上。

PdfFontInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | 将此字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | 此字体的内容，以字节数组形式；如果仅有元数据而二进制内容不可用，则为 None。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | 字体的族名称，不含样式；永不为 None 或空字符串。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | 此字体的格式。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | 该属性指示字体是否嵌入在 PDF 文档中并加载到 Viewer 实例中（`True`），否则为否。 |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | 该属性指示此字体是否存在（已安装）于运行 GroupDocs.Viewer 的操作系统中。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | 字体的样式；可能为 Regular、Bold、Italic 或 Bold Italic。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
