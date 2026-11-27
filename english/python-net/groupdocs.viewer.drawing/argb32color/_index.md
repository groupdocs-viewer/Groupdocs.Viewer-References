---
title: Argb32Color class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents a 32-bit ARGB color with 8 bits per channel (Alpha, Red, Green, Blue) and supports transparency."
type: docs
url: /python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Represents a 32-bit ARGB color with 8 bits per channel (Alpha, Red, Green, Blue) and supports transparency.

This type is designed to be useful for (but not limited to) CSS operations. See more: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

The Argb32Color type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Checks this color against the specified [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) for equality. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Checks this color against the specified [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) for equality. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Determines whether this color equals the specified uncasted color. |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Creates a Argb32Color instance from its 32-bit component (alpha, red, green, and blue) values, compatible with the value produced by `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Creates a new [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance from the specified one, but with a re-defined alpha (opacity) value. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Creates a new Argb32Color instance from a specified Rgb24Color, but with a specified alpha (opacity) value. |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Creates an [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) value from the specified red, green, and blue channels, with the alpha channel set to fully opaque. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Creates a [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) value from the specified red, green, blue, and alpha channel values. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Creates a fully opaque (A=255) color from a single byte value applied to all channels. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Returns the Hue‑Saturation‑Lightness (HSL) lightness/brightness for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Returns a hash code that defines the current color. Not compatible with `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Returns the Hue‑Saturation‑Lightness (HSL) hue value, in degrees, for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | The Hue‑Saturation‑Lightness (HSL) saturation for this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Returns the ARGB value of this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance, compatible with `System.Drawing.Color.ToArgb()` method. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to a hexadecimal `##RRGGBB` string without the alpha channel. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to the hexadecimal notation `##RRGGBBAA` as a string with alpha channel. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to the 'rgb' CSS function notation, omitting the alpha channel. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serializes this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance to the 'rgba' CSS function notation. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serializes this Argb32Color instance to the most appropriate CSS function notation depending on translucency. |

### Properties
| Property | Description |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | The alpha component of the color as an 8-bit unsigned integer in the range 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | The alpha component of the color as a float in the range 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | The blue component of the color as an 8-bit unsigned integer in the range 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | The green component of the color as an 8-bit unsigned integer in the range 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | The property indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is default (transparent) – all four channels are set to 0. |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | The property indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is uninitialized (all four channels are set to 0). It is equivalent to the default or transparent color and mirrors [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | The property indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is fully opaque, without transparency (its Alpha channel has max value). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | The property indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is fully transparent, i.e., its Alpha channel is 0, so the R, G, and B channels have no visible effect. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | The `is_translucent` property indicates whether this [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instance is translucent (not fully transparent, but also not fully opaque). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | The red component of the color as an 8-bit unsigned integer in the range 0..255. |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | The 32-bit signed integer representation of the color. |

### Fields
| Field | Description |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Returns an empty color, which has no channels info and is fully transparent. Same as ''. Default value. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Fully transparent empty color. The same as default '' color value. |

### Example

```python
from groupdocs.viewer.drawing import Argb32Color

# Create a yellow color (RGB 255, 255, 0) with full opacity
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### See Also
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
