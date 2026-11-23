---
title: "Argb32Color"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "表示以 ARGB 格式的 32 位颜色，每个通道（Alpha、Red、Green、Blue）各占 8 位。支持透明度。"
type: docs
weight: 950
url: /zh/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

表示 ARGB 格式的 32 位颜色，每个通道（Alpha、Red、Green、Blue）占 8 位。支持透明度。

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | 获取颜色的 alpha 部分，作为 8 位无符号整数 [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | 获取颜色的 alpha 部分，以百分比表示，范围为 (0..1)。 |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | 获取颜色的 blue 部分，作为 8 位无符号整数 [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | 获取颜色的 green 部分，作为 8 位无符号整数 [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | 指示此 [`Argb32Color`](../argb32color) 实例是否为默认（透明）——所有 4 个通道均设为 0。等同于 [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | 指示此 [`Argb32Color`](../argb32color) 颜色实例是否未初始化——所有 4 个通道均设为 0。等同于默认和透明。等同于 [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | 指示此 [`Argb32Color`](../argb32color) 实例是否完全不透明，即没有透明度（其 Alpha 通道为最大值） |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | 指示此 [`Argb32Color`](../argb32color) 实例是否完全透明——其 Alpha 通道为最小值 (0)，因此其他 R、G、B 通道没有可见效果。 |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | 指示此 [`Argb32Color`](../argb32color) 实例是否为半透明（不是完全透明，也不是完全不透明） |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | 获取颜色的红色部分，作为 8 位无符号整数 [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | 获取颜色的 Int32 值，作为 32 位有符号整数 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | 从其 32 位组件（alpha、red、green 和 blue）值创建一个 [`Argb32Color`](../argb32color) 实例，与 `System.Drawing.Color.ToArgb()` 方法产生的值兼容 |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | 从指定的值创建一个新的 [`Argb32Color`](../argb32color) 实例，但使用重新定义的 alpha（不透明度）值 |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | 从指定的 [`Rgb24Color`](../rgb24color) 创建一个新的 [`Argb32Color`](../argb32color) 实例，但使用指定的 alpha（不透明度）值 |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | 从指定的红、绿、蓝通道创建一个 [`Argb32Color`](../argb32color) 值，Alpha 通道为完全不透明 |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | 从指定的红、绿、蓝和 Alpha 通道创建一个 [`Argb32Color`](../argb32color) 值 |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | 从单一数值创建一个完全不透明 (A=255) 的颜色，该数值将应用于所有通道 |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | 检查此颜色与指定的 [`Argb32Color`](../argb32color) 颜色是否相等 |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | 检查此颜色与指定的未转换颜色 |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | 检查此颜色与指定的 [`Rgb24Color`](../rgb24color) 颜色是否相等 |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | 返回此 [`Argb32Color`](../argb32color) 实例的色相-饱和度-亮度 (HSL) 亮度/明度。 |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | 返回定义当前颜色的哈希码。与 GetHashCode 不兼容 |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | 返回此 [`Argb32Color`](../argb32color) 实例的色相-饱和度-亮度 (HSL) 色相值（以度为单位）。如果 R == G == B，则色相没有意义，返回值为 0。 |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | 此 [`Argb32Color`](../argb32color) 实例的色相-饱和度-亮度 (HSL) 饱和度 |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | 返回此 [`Argb32Color`](../argb32color) 实例的 ARGB 值，与 `System.Drawing.Color.ToArgb()` 方法兼容 |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | 将此 [`Argb32Color`](../argb32color) 实例序列化为十六进制表示 `##RRGGBB`，作为不含 alpha 通道的字符串 |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | 将此 [`Argb32Color`](../argb32color) 实例序列化为十六进制表示 `##RRGGBBAA`，作为含 alpha 通道的字符串 |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | 将此 [`Argb32Color`](../argb32color) 实例序列化为 'rgb' CSS 函数表示法。序列化时将省略该颜色的 alpha 通道。 |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | 将此 [`Argb32Color`](../argb32color) 实例序列化为 'rgba' CSS 函数表示法 |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | 根据半透明程度，将此 [`Argb32Color`](../argb32color) 实例序列化为最合适的 CSS 函数表示法 |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | 比较两个 [`Argb32Color`](../argb32color) 颜色并返回布尔值，指示两者是否匹配。（2 个运算符） |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | 显式将 32 位 [`Argb32Color`](../argb32color) 转换为 24 位 [`Rgb24Color`](../rgb24color)。源 [`Argb32Color`](../argb32color) 的 alpha 通道将在转换后丢失，因为 [`Rgb24Color`](../rgb24color) 不支持透明度。 |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | 隐式将 24 位 [`Rgb24Color`](../rgb24color) 转换为 32 位 [`Argb32Color`](../argb32color)。输出的 [`Argb32Color`](../argb32color) 的 alpha 通道将被设置为 `255` —— 完全不透明。 |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | 比较两个[`Argb32Color`](../argb32color)颜色，并返回一个布尔值，指示这两个是否不匹配。（2 个运算符） |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | 返回一个空颜色，该颜色没有通道信息且完全透明。等同于'[`Transparent`](./transparent)'。默认值。 |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | 完全透明的空颜色。等同于默认的'[`Empty`](./empty)'颜色值。 |

### 备注

此类型旨在用于（但不限于）CSS 操作。更多信息请参阅：https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 另见

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
