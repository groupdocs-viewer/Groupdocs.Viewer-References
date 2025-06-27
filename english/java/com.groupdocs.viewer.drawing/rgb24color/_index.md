---
title: Rgb24Color
second_title: GroupDocs.Viewer for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.groupdocs.viewer.drawing/rgb24color/
---
**Inheritance:**
java.lang.Object
```
public class Rgb24Color
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Rgb24Color(int r, int g, int b)](#Rgb24Color-int-int-int-) | Private constructor to create a color from red, green, and blue channels. |
## Methods

| Method | Description |
| --- | --- |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Creates a new Rgb24Color from specified red, green, and blue channel values. |
| [getR()](#getR--) | Gets the red channel value. |
| [getG()](#getG--) | Gets the green channel value. |
| [getB()](#getB--) | Gets the blue channel value. |
| [isDefault()](#isDefault--) | Returns true if the color is the default black color (all channels are zero). |
| [getBrightness()](#getBrightness--) | Calculates the brightness (lightness) of this color in HSL color space. |
| [getHue()](#getHue--) | Calculates the hue of this color in degrees (HSL color space). |
| [getSaturation()](#getSaturation--) | Calculates the saturation of this color in HSL color space. |
| [toArgb()](#toArgb--) | Returns the 32-bit ARGB representation of this color. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [toRGB()](#toRGB--) | Returns the CSS rgb() function string representation of the color. |
| [toHex()](#toHex--) | Returns the hexadecimal string representation of the color. |
| [toString()](#toString--) |  |
### Rgb24Color(int r, int g, int b) {#Rgb24Color-int-int-int-}
```
public Rgb24Color(int r, int g, int b)
```


Private constructor to create a color from red, green, and blue channels. Values are clamped to the [0..255] range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Rgb24Color fromRgb(int red, int green, int blue)
```


Creates a new Rgb24Color from specified red, green, and blue channel values. The input values are clamped to the valid range [0..255].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| red | int | Red channel value |
| green | int | Green channel value |
| blue | int | Blue channel value |

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) - New Rgb24Color instance
### getR() {#getR--}
```
public int getR()
```


Gets the red channel value.

**Returns:**
int - Red channel [0..255]
### getG() {#getG--}
```
public int getG()
```


Gets the green channel value.

**Returns:**
int - Green channel [0..255]
### getB() {#getB--}
```
public int getB()
```


Gets the blue channel value.

**Returns:**
int - Blue channel [0..255]
### isDefault() {#isDefault--}
```
public boolean isDefault()
```


Returns true if the color is the default black color (all channels are zero).

**Returns:**
boolean - True if black, otherwise false
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Calculates the brightness (lightness) of this color in HSL color space.

**Returns:**
float - Brightness as a float in range [0..1]
### getHue() {#getHue--}
```
public float getHue()
```


Calculates the hue of this color in degrees (HSL color space). Returns 0 if the color is grayscale (red = green = blue).

**Returns:**
float - Hue in degrees [0..360)
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```


Calculates the saturation of this color in HSL color space.

**Returns:**
float - Saturation as a float in range [0..1]
### toArgb() {#toArgb--}
```
public int toArgb()
```


Returns the 32-bit ARGB representation of this color. Alpha is always set to 255 (fully opaque).

**Returns:**
int - ARGB color as int
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### toRGB() {#toRGB--}
```
public String toRGB()
```


Returns the CSS rgb() function string representation of the color.

**Returns:**
java.lang.String - String in format "rgb(r, g, b)"
### toHex() {#toHex--}
```
public String toHex()
```


Returns the hexadecimal string representation of the color.

**Returns:**
java.lang.String - String in format "\#RRGGBB"
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
