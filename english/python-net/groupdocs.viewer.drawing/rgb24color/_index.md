---
title: Rgb24Color class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 30
---

## Rgb24Color class

Represents 24-bit color in RGB format, with 8 bits per every channel (Red, Green, Blue). Does not support transparency.



The Rgb24Color type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/#) | Constructs a new instance of Rgb24Color |


### Properties
| Property | Description |
| :- | :- |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r) | Gets the red part of the color as 8-bit unsigned integer [0..255] |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g) | Gets the green part of the color as 8-bit unsigned integer [0..255] |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b) | Gets the blue part of the color as 8-bit unsigned integer [0..255] |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default) | Indicates whether this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance is default (Black) - all 3 channels are set to 0. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#groupdocs.viewer.drawing.Argb32Color) | Checks this color with specified [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color) color for equality |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#groupdocs.viewer.drawing.Rgb24Color) | Checks this color with specified [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) color for equality |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#int-int-int) | Creates one [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) value from specified Red, Green, Blue channels |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/#) | Returns the Hue-Saturation-Lightness (HSL) lightness/brightness for this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/#) | Returns the Hue-Saturation-Lightness (HSL) hue value, in degrees, for this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance. If R == G == B, the hue is meaningless, and the return value is 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/#) | The Hue-Saturation-Lightness (HSL) saturation for this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/#) | Returns the ARGB value of this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance, compatible with Color |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/#) | Serializes this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color) instance to the 'rgb' CSS function notation. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/#) | Returns this color in hexadecimal string representation |



### Remarks 


This type is designed to be useful for (but not limited to) CSS operations. See more:
https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### See Also
* module [`groupdocs.viewer.drawing`](..)
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color)
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color)
