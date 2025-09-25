---
title: Argb32Color
second_title: GroupDocs.Viewer for Java API Reference
description: Represents 32-bit color in ARGB format with 8 bits per channel Alpha Red Green Blue.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.drawing/argb32color/
---
**Inheritance:**
java.lang.Object
```
public class Argb32Color
```

Represents 32-bit color in ARGB format, with 8 bits per channel (Alpha, Red, Green, Blue). Supports transparency. Designed to be useful for (but not limited to) CSS operations. See more: https://developer.mozilla.org/en-US/docs/Web/CSS/color\_value
## Constructors

| Constructor | Description |
| --- | --- |
| [Argb32Color(int alpha, int red, int green, int blue)](#Argb32Color-int-int-int-int-) | Private constructor, initializes ARGB channels. |
## Fields

| Field | Description |
| --- | --- |
| [EMPTY](#EMPTY) |  |
| [TRANSPARENT](#TRANSPARENT) |  |
## Methods

| Method | Description |
| --- | --- |
| [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Create an Argb32Color from individual RGBA channels. |
| [fromArgb(int argb)](#fromArgb-int-) | Create an Argb32Color from a 32-bit ARGB int value (same as System.Drawing.Color.ToArgb()). |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Create an opaque Argb32Color from RGB channels (alpha = 255). |
| [fromSingleValueRgb(int value)](#fromSingleValueRgb-int-) | Create a grayscale opaque Argb32Color from a single value applied to R, G, B. |
| [getValue()](#getValue--) | Gets the 32-bit signed integer representation of this color. |
| [getAlpha()](#getAlpha--) | Returns the alpha channel [0..255] |
| [getAlphaFraction()](#getAlphaFraction--) | Returns the alpha channel as fraction [0..1] |
| [getRed()](#getRed--) | Returns the red channel [0..255] |
| [getGreen()](#getGreen--) | Returns the green channel [0..255] |
| [getBlue()](#getBlue--) | Returns the blue channel [0..255] |
| [getArgbValue()](#getArgbValue--) | Returns the 32-bit ARGB integer value |
| [isEmpty()](#isEmpty--) | Indicates if this color is empty (all channels 0) |
| [isDefault()](#isDefault--) | Indicates if instance is default (Transparent) - all 4 channels are set to 0. |
| [isFullyTransparent()](#isFullyTransparent--) | Indicates if this color is fully transparent (alpha == 0) |
| [isFullyOpaque()](#isFullyOpaque--) | Indicates if this color is fully opaque (alpha == 255) |
| [isTranslucent()](#isTranslucent--) | Indicates if this color is translucent (alpha between 1 and 254) |
| [getBrightness()](#getBrightness--) | Calculates brightness/lightness of the color (HSL model). |
| [getHue()](#getHue--) | Calculates hue of the color in degrees [0..360]. |
| [getSaturation()](#getSaturation--) | Calculates saturation of the color (HSL model). |
| [toArgb()](#toArgb--) | Returns the 32-bit ARGB value of this color instance, compatible with System.Drawing.Color.ToArgb() |
| [toRGBA()](#toRGBA--) | Serializes this Argb32Color instance to the 'rgba' CSS function notation. |
| [toRGB()](#toRGB--) | Serializes this instance to CSS rgb() string notation (without alpha). |
| [toHexRGBA()](#toHexRGBA--) | Serializes this instance to hexadecimal \#RRGGBBAA notation. |
| [toHexRGB()](#toHexRGB--) | Serializes this instance to hexadecimal \#RRGGBB notation (without alpha). |
| [toString()](#toString--) | Returns the string representation using the most appropriate CSS notation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Equality comparison with another Argb32Color. |
| [hashCode()](#hashCode--) |  |
| [equals(Argb32Color other)](#equals-com.groupdocs.viewer.drawing.Argb32Color-) | Compares this color with another Argb32Color. |
| [equals(Rgb24Color other)](#equals-com.groupdocs.viewer.drawing.Rgb24Color-) | Compares this color with a Rgb24Color. |
| [toRgb24Color()](#toRgb24Color--) | Cast this Argb32Color to Rgb24Color, losing alpha channel. |
| [fromRgb24Color(Rgb24Color rgbColor)](#fromRgb24Color-com.groupdocs.viewer.drawing.Rgb24Color-) | Create Argb32Color from Rgb24Color with alpha set to 255. |
### Argb32Color(int alpha, int red, int green, int blue) {#Argb32Color-int-int-int-int-}
```
public Argb32Color(int alpha, int red, int green, int blue)
```


Private constructor, initializes ARGB channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | int | alpha channel (0-255) |
| red | int | red channel (0-255) |
| green | int | green channel (0-255) |
| blue | int | blue channel (0-255) |

### EMPTY {#EMPTY}
```
public static final Argb32Color EMPTY
```


### TRANSPARENT {#TRANSPARENT}
```
public static final Argb32Color TRANSPARENT
```


### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static Argb32Color fromRgba(int red, int green, int blue, int alpha)
```


Create an Argb32Color from individual RGBA channels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int |  |
| green | int |  |
| blue | int |  |
| alpha | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### fromArgb(int argb) {#fromArgb-int-}
```
public static Argb32Color fromArgb(int argb)
```


Create an Argb32Color from a 32-bit ARGB int value (same as System.Drawing.Color.ToArgb()).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Argb32Color fromRgb(int red, int green, int blue)
```


Create an opaque Argb32Color from RGB channels (alpha = 255).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int |  |
| green | int |  |
| blue | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### fromSingleValueRgb(int value) {#fromSingleValueRgb-int-}
```
public static Argb32Color fromSingleValueRgb(int value)
```


Create a grayscale opaque Argb32Color from a single value applied to R, G, B.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getValue() {#getValue--}
```
public int getValue()
```


Gets the 32-bit signed integer representation of this color. This value is typically used as a packed ARGB value.

**Returns:**
int - The 32-bit integer value representing the color.
### getAlpha() {#getAlpha--}
```
public int getAlpha()
```


Returns the alpha channel [0..255]

**Returns:**
int
### getAlphaFraction() {#getAlphaFraction--}
```
public double getAlphaFraction()
```


Returns the alpha channel as fraction [0..1]

**Returns:**
double
### getRed() {#getRed--}
```
public int getRed()
```


Returns the red channel [0..255]

**Returns:**
int
### getGreen() {#getGreen--}
```
public int getGreen()
```


Returns the green channel [0..255]

**Returns:**
int
### getBlue() {#getBlue--}
```
public int getBlue()
```


Returns the blue channel [0..255]

**Returns:**
int
### getArgbValue() {#getArgbValue--}
```
public int getArgbValue()
```


Returns the 32-bit ARGB integer value

**Returns:**
int
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Indicates if this color is empty (all channels 0)

**Returns:**
boolean
### isDefault() {#isDefault--}
```
public boolean isDefault()
```


Indicates if instance is default (Transparent) - all 4 channels are set to 0.

**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public boolean isFullyTransparent()
```


Indicates if this color is fully transparent (alpha == 0)

**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public boolean isFullyOpaque()
```


Indicates if this color is fully opaque (alpha == 255)

**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public boolean isTranslucent()
```


Indicates if this color is translucent (alpha between 1 and 254)

**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Calculates brightness/lightness of the color (HSL model).

**Returns:**
float - float in [0..1]
### getHue() {#getHue--}
```
public float getHue()
```


Calculates hue of the color in degrees [0..360]. Returns 0 if color is grayscale (R=G=B).

**Returns:**
float
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Calculates saturation of the color (HSL model).

**Returns:**
float - float in [0..1]
### toArgb() {#toArgb--}
```
public int toArgb()
```


Returns the 32-bit ARGB value of this color instance, compatible with System.Drawing.Color.ToArgb()

**Returns:**
int
### toRGBA() {#toRGBA--}
```
public String toRGBA()
```


Serializes this Argb32Color instance to the 'rgba' CSS function notation.

**Returns:**
java.lang.String - A string formatted as 'rgba(r, g, b, a)'.
### toRGB() {#toRGB--}
```
public String toRGB()
```


Serializes this instance to CSS rgb() string notation (without alpha).

**Returns:**
java.lang.String
### toHexRGBA() {#toHexRGBA--}
```
public String toHexRGBA()
```


Serializes this instance to hexadecimal \#RRGGBBAA notation.

**Returns:**
java.lang.String
### toHexRGB() {#toHexRGB--}
```
public String toHexRGB()
```


Serializes this instance to hexadecimal \#RRGGBB notation (without alpha).

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns the string representation using the most appropriate CSS notation.

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equality comparison with another Argb32Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Argb32Color other) {#equals-com.groupdocs.viewer.drawing.Argb32Color-}
```
public boolean equals(Argb32Color other)
```


Compares this color with another Argb32Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Argb32Color](../../com.groupdocs.viewer.drawing/argb32color) |  |

**Returns:**
boolean
### equals(Rgb24Color other) {#equals-com.groupdocs.viewer.drawing.Rgb24Color-}
```
public boolean equals(Rgb24Color other)
```


Compares this color with a Rgb24Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) |  |

**Returns:**
boolean
### toRgb24Color() {#toRgb24Color--}
```
public Rgb24Color toRgb24Color()
```


Cast this Argb32Color to Rgb24Color, losing alpha channel.

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### fromRgb24Color(Rgb24Color rgbColor) {#fromRgb24Color-com.groupdocs.viewer.drawing.Rgb24Color-}
```
public static Argb32Color fromRgb24Color(Rgb24Color rgbColor)
```


Create Argb32Color from Rgb24Color with alpha set to 255.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rgbColor | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
