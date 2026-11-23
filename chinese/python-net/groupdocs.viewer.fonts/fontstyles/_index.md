---
title: "FontStyles 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示文档中使用的字体的四种可能样式：Regular、Bold、Italic 或 Bold Italic。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

表示文档中使用的字体的四种可能样式：Regular、Bold、Italic 或 Bold Italic。

具有便利 API 和组合操作的不可变结构体。

FontStyles 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | 从指定的粗体和斜体标志初始化 FontStyles 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | 指示此 FontStyles 实例是否等于指定的实例。 |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | 指示此 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 实例是否等于指定的未转换对象。 |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | 返回此实例的哈希码。 |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | 返回此字体样式的名称，等同于 [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/)。 |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | 尝试将指定的原始字符串解析为字体样式名称。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | 该属性指示此 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 实例的粗体标志是已启用 (`True`) 还是已禁用 (`False`)。 |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | 此 [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) 实例的斜体标志状态；如果已启用则为 True，未启用则为 False。 |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | 此字体样式的名称。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | 常规字体样式，默认值（无粗体和斜体） |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | 粗体字体样式（仅粗体，不含斜体） |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | 斜体字体样式（仅斜体，不含粗体） |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | 粗斜体字体样式（粗体和斜体一起） |

### 另见
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
