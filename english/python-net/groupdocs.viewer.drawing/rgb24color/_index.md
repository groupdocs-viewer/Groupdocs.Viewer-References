---
title: Rgb24Color
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 30
url: /python-net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color class

Represents 24-bit color in RGB format, with 8 bits per every channel (Red, Green, Blue). Does not support transparency.

The Rgb24Color type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Rgb24Color()|Initializes a new instance of the Rgb24Color class|
## Properties
| Name | Description |
| :- | :- |
|r|Gets the red part of the color as 8-bit unsigned integer [0..255]|
|g|Gets the green part of the color as 8-bit unsigned integer [0..255]|
|b|Gets the blue part of the color as 8-bit unsigned integer [0..255]|
|is_default|Indicates whether this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance is default (Black) - all 3 channels are set to 0.|
## Methods
| Name | Description |
| :- | :- |
|equals(other)|Checks this color with specified [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) color for equality|
|equals(other)|Checks this color with specified [Argb32Color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) color for equality|
|from_rgb(red, green, blue)|Creates one [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) value from specified Red, Green, Blue channels|
|get_brightness()|Returns the Hue-Saturation-Lightness (HSL) lightness/brightness for this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance.|
|get_hue()|Returns the Hue-Saturation-Lightness (HSL) hue value, in degrees, for this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance. If R == G == B, the hue is meaningless, and the return value is 0.|
|get_saturation()|The Hue-Saturation-Lightness (HSL) saturation for this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance|
|to_argb()|Returns the ARGB value of this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance, compatible with aspose.pydrawing.Color|
|to_rgb()|Serializes this [Rgb24Color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance to the 'rgb' CSS function notation.|
|to_hex()|Returns this color in hexadecimal string representation|

### See Also

* namespace [groupdocs.viewer.drawing](/viewer/python-net/groupdocs.viewer.drawing/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

