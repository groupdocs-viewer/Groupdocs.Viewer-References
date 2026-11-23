---
title: "WordProcessingSubstitutedFontInfo 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "封装来自 WordProcessing 文档的单个字体的元信息和二进制数据，该字体最初未在加载的 Viewer 实例文档中使用，但作为这些字体的替代字体…"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

封装从 WordProcessing 文档中获取的单个字体的元信息和二进制数据，该字体最初未在已加载的 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例文档中使用，但作为目标机器上未找到的字体的替代字体。替代字体仅存在于 WordProcessing 格式系列中。

不可变结构体。其实例由 [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 公共 API 生成并返回，通常不应由用户创建。详情请参阅文档：https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | 将字体信息序列化为 @font-face 规则并写入指定的文本写入器。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | 返回包含字体信息的调试字符串，格式为 "original-name -> substituted-name style, format"。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | 替代字体的内容，以字节数组形式。它永不为 None。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | 替代字体的族名称，不含样式。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | 此替代（非原始）字体的格式。 |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | 原始字体的族名称，在目标机器上找不到，不含样式。永不为 null 或空字符串。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | 原始字体的样式 — 可能为 Regular、Bold、Italic 或 Bold Italic。 |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
