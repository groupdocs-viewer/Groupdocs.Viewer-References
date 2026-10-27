---
title: "Rgb24Color 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示 24 位 RGB 颜色，每个通道（Red、Green、Blue）为 8 位，且不支持透明度。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

表示 24 位 RGB 颜色，每个通道（Red、Green、Blue）为 8 位，且不支持透明度。

此类型旨在对 CSS 操作（但不限于此）有用。了解更多：https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Rgb24Color 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | 确定此颜色是否等于指定的 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | 检查此颜色与指定的 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 颜色是否相等。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | 检查此颜色与指定的未转换的颜色是否相等。 |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | 从指定的红、绿、蓝通道值创建一个 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 值。 |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | 返回此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例的色相‑饱和度‑亮度 (HSL) 亮度/明度。 |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | 返回定义当前颜色的哈希码。此哈希码与 `System.Drawing.Color.GetHashCode` 不兼容。 |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | 返回颜色在 HSL 色彩空间中的色相分量，以度数表示。如果颜色是灰度的 (R == G == B)，则色相未定义，方法返回 0。 |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | 此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例的色相‑饱和度‑亮度 (HSL) 饱和度。 |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | 返回此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例的 ARGB 值，兼容 `System.Drawing.Color`。 |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | 以十六进制字符串形式返回此颜色。 |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | 将此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例序列化为 'rgb' CSS 函数表示法。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | 将此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例序列化为 'rgb(r, g, b)' 格式。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | 颜色的蓝色分量，作为 8 位无符号整数 [0..255]。 |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | 颜色的绿色分量，以 0..255 范围内的 8 位无符号整数表示。 |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | 此属性指示此 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 实例是否为默认（黑色）——所有三个通道均设置为 0。 |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | 颜色的红色分量，以 0..255 范围内的 8 位无符号整数表示。 |

### 另见
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
