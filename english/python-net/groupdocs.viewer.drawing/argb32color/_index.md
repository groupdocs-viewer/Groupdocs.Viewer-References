---
title: Argb32Color
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /python-net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color class

Represents 32-bit color in ARGB format, with 8 bits per every channel (Alpha, Red, Green, Blue). Supports transparency.

The Argb32Color type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Argb32Color()|Initializes a new instance of the Argb32Color class|
## Properties
| Name | Description |
| :- | :- |
|value|Gets the Int32 value of the color as 32-bit signed integer|
|a|Gets the alpha part of the color as 8-bit unsigned integer [0..255]|
|alpha|Gets the alpha part of the color in percent in (0..1) range.|
|r|Gets the red part of the color as 8-bit unsigned integer [0..255]|
|g|Gets the green part of the color as 8-bit unsigned integer [0..255]|
|b|Gets the blue part of the color as 8-bit unsigned integer [0..255]|
|is_empty|Indicates whether this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) color instance is uninitialized - all 4 channels are set to 0. Same as Default and Transparent. Same as [None](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)|
|is_fully_transparent|Indicates whether this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is fully transparent - its Alpha channel has the min (0) value, so other R, G, and B channels has no visible effect.|
|is_translucent|Indicates whether this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is translucent (not fully transparent, but also not fully opaque)|
|is_fully_opaque|Indicates whether this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is fully opaque, without transparency (its Alpha channel has max value)|
|EMPTY|Returns an empty color, which has no channels info and is fully transparent. Same as '[None](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)'. Default value.|
|TRANSPARENT|Fully transparent empty color. The same as default '[None](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)' color value.|
## Methods
| Name | Description |
| :- | :- |
|from_other_with_alpha(other, new_alpha)|Creates a new [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance from specified, but with re-defined alpha (opacity) value|
|from_other_with_alpha(other, new_alpha)|Creates a new [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance from specified [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), but with specified alpha (opacity) value|
|equals(other)|Checks this color with specified [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) color for equality|
|equals(other)|Checks this color with specified [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) color for equality|
|from_rgba(red, green, blue, alpha)|Creates one [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) value from specified Red, Green, Blue, and Alpha channels|
|from_argb(argb)|Creates a [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance from its 32-bit component (alpha, red, green, and blue) values, compatible with value, produced by the|
|from_rgb(red, green, blue)|Creates one [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) value from specified Red, Green, Blue, and Alpha channels|
|from_single_value_rgb(value)|Creates a fully opaque (A=255) color from single value, which will be applied to all channels|
|get_brightness()|Returns the Hue-Saturation-Lightness (HSL) lightness/brightness for this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance.|
|get_hue()|Returns the Hue-Saturation-Lightness (HSL) hue value, in degrees, for this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance. If R == G == B, the hue is meaningless, and the return value is 0.|
|get_saturation()|The Hue-Saturation-Lightness (HSL) saturation for this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance|
|to_argb()|Returns the ARGB value of this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance, compatible with|
|to_rgba()|Serializes this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to the 'rgba' CSS function notation|
|to_rgb()|Serializes this [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to the 'rgba' CSS function notation|

### See Also

* namespace [groupdocs.viewer.drawing](/viewer/python-net/groupdocs.viewer.drawing/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

