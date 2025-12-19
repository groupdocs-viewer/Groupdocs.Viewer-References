---
title: Argb32Color class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---

## Argb32Color class

Represents 32-bit color in ARGB format, with 8 bits per every channel (Alpha, Red, Green, Blue). Supports transparency.



The Argb32Color type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/#) | Constructs a new instance of Argb32Color |


### Properties
| Property | Description |
| :- | :- |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value) | Gets the Int32 value of the color as 32-bit signed integer |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a) | Gets the alpha part of the color as 8-bit unsigned integer [0..255] |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha) | Gets the alpha part of the color in percent in (0..1) range. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r) | Gets the red part of the color as 8-bit unsigned integer [0..255] |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g) | Gets the green part of the color as 8-bit unsigned integer [0..255] |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b) | Gets the blue part of the color as 8-bit unsigned integer [0..255] |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty) | Indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) color instance is uninitialized - all 4 channels are set to 0. Same as Default and Transparent. Same as [`Argb32Color.IsDefault`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent) | Indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance is fully transparent - its Alpha channel has the min (0) value, so other R, G, and B channels has no visible effect. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent) | Indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance is translucent (not fully transparent, but also not fully opaque) |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque) | Indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance is fully opaque, without transparency (its Alpha channel has max value) |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty) | Returns an empty color, which has no channels info and is fully transparent. Same as '[`Argb32Color.Transparent`](/viewer/python-net/groupdocs.viewer.drawing/argb32color)'. Default value. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent) | Fully transparent empty color. The same as default '[`Argb32Color.Empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color)' color value. |


### Methods
| Method | Description |
| :- | :- |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#groupdocs.viewer.drawing.Argb32Color-int) | Creates a new [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance from specified, but with re-defined alpha (opacity) value |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#groupdocs.viewer.drawing.Rgb24Color-int) | Creates a new [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance from specified [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color), but with specified alpha (opacity) value |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#groupdocs.viewer.drawing.Argb32Color) | Checks this color with specified [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) color for equality |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#groupdocs.viewer.drawing.Rgb24Color) | Checks this color with specified [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) color for equality |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#int-int-int-int) | Creates one [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) value from specified Red, Green, Blue, and Alpha channels |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#int) | Creates a [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance from its 32-bit component (alpha, red, green, and blue) values, compatible with value, produced by the `System.Drawing.Color.ToArgb()` method |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#int-int-int) | Creates one [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) value from specified Red, Green, Blue channels, while Alpha channel is fully opaque |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#int) | Creates a fully opaque (A=255) color from single value, which will be applied to all channels |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/#) | Returns the Hue-Saturation-Lightness (HSL) lightness/brightness for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/#) | Returns the Hue-Saturation-Lightness (HSL) hue value, in degrees, for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance. If R == G == B, the hue is meaningless, and the return value is 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/#) | The Hue-Saturation-Lightness (HSL) saturation for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/#) | Returns the ARGB value of this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance, compatible with `System.Drawing.Color.ToArgb()` method |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/#) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance to the 'rgba' CSS function notation |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/#) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) instance to the 'rgb' CSS function notation. Alpha channel of this color will be omitted during serialization. |



### Remarks 


This type is designed to be useful for (but not limited to) CSS operations. See more:
https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### See Also
* module [`groupdocs.viewer.drawing`](..)
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color)
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color)
