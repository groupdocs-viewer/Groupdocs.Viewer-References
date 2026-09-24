---
title: Rgb24Color class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents 24-bit RGB color with 8 bits per channel (Red, Green, Blue) and no transparency."
type: docs
url: /python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Represents 24-bit RGB color with 8 bits per channel (Red, Green, Blue) and no transparency.

This type is designed to be useful for (but not limited to) CSS operations. See more: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

The Rgb24Color type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Determines whether this color is equal to the specified [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Checks this color with specified [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) color for equality. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Checks this color against the specified uncasted color. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Creates a [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) value from the specified red, green, and blue channel values. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Returns the Hue‑Saturation‑Lightness (HSL) lightness/brightness for this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Returns a hash code that defines the current color. Not compatible with `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Returns the hue component of the color in the HSL color space, expressed in degrees. If the color is grayscale (R == G == B), the hue is undefined and the method returns 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | The Hue‑Saturation‑Lightness (HSL) saturation for this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Returns the ARGB value of this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance, compatible with `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Returns this color in hexadecimal string representation. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Serializes this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance to the 'rgb' CSS function notation. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Serializes this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance to 'rgb(r, g, b)' format. |

### Properties
| Property | Description |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | The blue component of the color as an 8-bit unsigned integer [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | The green component of the color as an 8-bit unsigned integer in the range 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | The property indicates whether this [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) instance is the default (Black) – all three channels are set to 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | The red component of the color as an 8-bit unsigned integer (0..255). |

### See Also
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
