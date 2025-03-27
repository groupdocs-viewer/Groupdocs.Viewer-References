---
title: Argb32Color
second_title: GroupDocs.Viewer for .NET API Reference
description: Represents 32bit color in ARGB format with 8 bits per every channel Alpha Red Green Blue. Supports transparency.
type: docs
weight: 40
url: /net/groupdocs.viewer.drawing/argb32color/
---
## Argb32Color structure

Represents 32-bit color in ARGB format, with 8 bits per every channel (Alpha, Red, Green, Blue). Supports transparency.

```csharp
public struct Argb32Color : IEquatable<>, IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Properties

| Name | Description |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Gets the alpha part of the color as 8-bit unsigned integer [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Gets the alpha part of the color in percent in (0..1) range. |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Gets the blue part of the color as 8-bit unsigned integer [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Gets the green part of the color as 8-bit unsigned integer [0..255] |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Indicates whether this [`Argb32Color`](../argb32color) color instance is uninitialized - all 4 channels are set to 0. Same as Default and Transparent. Same as IsDefault |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Indicates whether this [`Argb32Color`](../argb32color) instance is fully opaque, without transparency (its Alpha channel has max value) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Indicates whether this [`Argb32Color`](../argb32color) instance is fully transparent - its Alpha channel has the min (0) value, so other R, G, and B channels has no visible effect. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Indicates whether this [`Argb32Color`](../argb32color) instance is translucent (not fully transparent, but also not fully opaque) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Gets the red part of the color as 8-bit unsigned integer [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Gets the Int32 value of the color as 32-bit signed integer |

## Methods

| Name | Description |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Creates a [`Argb32Color`](../argb32color) instance from its 32-bit component (alpha, red, green, and blue) values, compatible with value, produced by the `System.Drawing.Color.ToArgb()` method |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Creates a new [`Argb32Color`](../argb32color) instance from specified, but with re-defined alpha (opacity) value |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Creates a new [`Argb32Color`](../argb32color) instance from specified [`Rgb24Color`](../rgb24color), but with specified alpha (opacity) value |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Creates one [`Argb32Color`](../argb32color) value from specified Red, Green, Blue channels, while Alpha channel is fully opaque |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Creates one [`Argb32Color`](../argb32color) value from specified Red, Green, Blue, and Alpha channels |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Creates a fully opaque (A=255) color from single value, which will be applied to all channels |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Checks this color with specified [`Argb32Color`](../argb32color) color for equality |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Tests if another object is equal to this [`Argb32Color`](../argb32color) instance. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Checks this color with specified [`Rgb24Color`](../rgb24color) color for equality |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Returns the Hue-Saturation-Lightness (HSL) lightness/brightness for this [`Argb32Color`](../argb32color) instance. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Returns a hash code that defines the current color. Not compatible with GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Returns the Hue-Saturation-Lightness (HSL) hue value, in degrees, for this [`Argb32Color`](../argb32color) instance. If R == G == B, the hue is meaningless, and the return value is 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | The Hue-Saturation-Lightness (HSL) saturation for this [`Argb32Color`](../argb32color) instance |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Returns the ARGB value of this [`Argb32Color`](../argb32color) instance, compatible with `System.Drawing.Color.ToArgb()` method |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Serializes this [`Argb32Color`](../argb32color) instance to the 'rgb' CSS function notation. Alpha channel of this color will be omitted during serialization. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Serializes this [`Argb32Color`](../argb32color) instance to the 'rgba' CSS function notation |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Serializes this [`Argb32Color`](../argb32color) instance to the most appropriate CSS function notation depending on translucency |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Compares two [`Argb32Color`](../argb32color) colors and returns a boolean indicating if the two do match. (2 operators) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Explicitly casts the 32-bit [`Argb32Color`](../argb32color) to 24-bit [`Rgb24Color`](../rgb24color). Alpha channel of the source [`Argb32Color`](../argb32color) will be lost after casting, because [`Rgb24Color`](../rgb24color) does not support transparency. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Implicitly casts the 24-bit [`Rgb24Color`](../rgb24color) to 32-bit [`Argb32Color`](../argb32color). Alpha channel of the output [`Argb32Color`](../argb32color) will be set to `255` - fully opaque. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Compares two [`Argb32Color`](../argb32color) colors and returns a boolean indicating if the two do not match. (2 operators) |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Returns an empty color, which has no channels info and is fully transparent. Same as '[`Transparent`](./transparent)'. Default value. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Fully transparent empty color. The same as default '[`Empty`](./empty)' color value. |

### Remarks

This type is designed to be useful for (but not limited to) CSS operations. See more: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### See Also

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
