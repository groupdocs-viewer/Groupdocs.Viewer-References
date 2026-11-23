---
title: "WordProcessingFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "封装来自加载到 Viewer 实例的 WordProcessing 文档的字体的元信息和二进制数据。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

封装从 WordProcessing 文档加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中的字体的元信息和二进制数据。

不可变结构体。

其实例由 [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 公共 API 生成并返回，通常不应由用户创建。

有关详细信息，请参阅文档：https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | 将字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | 返回关于此字体数据的调试信息，格式为：“name style, embedded/system, format”。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | 字体的替代族名。如果缺失，则为空字符串。 |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | 此字体的字符集。 |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | 此字体的内容，以字节数组形式。如果仅有此字体的元信息而二进制内容不可用，则属性返回 None。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | 字体的族名称，不含样式；永不为 None 或空字符串。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | 此字体的格式。 |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | 该属性指示此字体是嵌入在文档中并加载到 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例中（`True`），还是系统字体（`False`）。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | 字体的样式——可能是 Regular、Bold、Italic 或 Bold Italic。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
