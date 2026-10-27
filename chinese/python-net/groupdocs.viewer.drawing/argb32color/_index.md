---
title: "Argb32Color 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 ARGB 格式的 32 位颜色，每个通道（Alpha、Red、Green、Blue）占 8 位。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

表示 ARGB 格式的 32 位颜色，每个通道（Alpha、Red、Green、Blue）为 8 位。支持透明度。

此类型旨在对 CSS 操作（但不限于此）有用。了解更多：https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Argb32Color 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | 检查此颜色是否等于指定的 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | 确定此颜色是否等于指定的 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | 检查此颜色是否等于指定的未转换颜色。 |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | 从 32 位 ARGB 值创建 Argb32Color 实例，该值兼容由 `System.Drawing.Color.ToArgb()` 生成的值。 |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 从指定的实例创建一个新的 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例，但使用重新定义的 alpha（不透明度）值。 |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 从指定的 Rgb24Color 创建一个新的 Argb32Color 实例，但使用指定的 alpha（不透明度）值。 |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | 从指定的红、绿、蓝通道创建 Argb32Color 值，并将 Alpha 通道设置为完全不透明。 |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | 从指定的红、绿、蓝和 alpha 通道值创建一个 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 值。 |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | 从单个字节值（适用于所有通道）创建一个完全不透明 (A=255) 的颜色。 |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | 返回此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例的色相‑饱和度‑亮度 (HSL) 亮度/明度。 |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | 返回定义当前颜色的哈希码；该哈希码与 `System.Drawing.Color.GetHashCode` 不兼容。 |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | 返回此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例的色相‑饱和度‑亮度 (HSL) 色相值（以度为单位）；如果 R == G == B，则色相无意义，方法返回 0。 |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | 返回此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例的色相‑饱和度‑亮度 (HSL) 饱和度。 |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | 返回此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例的 ARGB 值，该值兼容 `System.Drawing.Color.ToArgb()` 方法。 |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | 将此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例序列化为十六进制表示 `##RRGGBB`，作为不包含 alpha 通道的字符串。 |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | 将此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例序列化为十六进制表示 `##RRGGBBAA`，作为包含 alpha 通道的字符串。 |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | 将此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例序列化为 `rgb` CSS 函数表示法，省略 alpha 通道。 |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | 将此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例序列化为 'rgba' CSS 函数表示法。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | 根据透明度，将 Argb32Color 实例序列化为最合适的 CSS 函数表示法。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | 颜色的 alpha 分量，以 0..255 范围内的 8 位无符号整数表示。 |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | 颜色的 alpha 分量，以 0..1 范围内的浮点数表示。 |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | 颜色的蓝色分量，以 0..255 范围内的 8 位无符号整数表示。 |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | 颜色的绿色分量，以 0..255 范围内的 8 位无符号整数表示。 |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | 该属性指示此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例是否为默认（透明），即四个通道全部为 0；它等价于 [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/)。 |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | 该属性指示此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例是否未初始化（四个通道全部为 0）。它等价于默认或透明颜色，并匹配 [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/)。 |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | 该属性指示此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例是否完全不透明，即没有透明度（其 Alpha 通道为最大值）。 |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | 该属性指示此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例是否完全透明——其 Alpha 通道为最小值（0），因此 R、G、B 通道不产生可见效果。 |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | 该属性指示此 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例是否为半透明（既非完全透明，也非完全不透明）。 |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | 颜色的红色分量，以 0..255 范围内的 8 位无符号整数表示。 |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | 颜色的 32 位有符号整数表示。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | 返回一个空颜色，该颜色没有通道信息且完全透明。等同于 ''。默认值。 |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | 完全透明的空颜色。与默认的 '' 颜色值相同。 |

### 示例

```python
from groupdocs.viewer.drawing import Argb32Color

# 创建一个完全不透明的黄色颜色（RGB 255, 255, 0）
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### 另见
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
