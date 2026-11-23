---
title: "Argb32Color"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar 32-bitars färg i ARGB-format med 8 bitar per kanal Alfa Röd Grön Blå."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.drawing/argb32color/
---
**Inheritance:**
java.lang.Object
```
public class Argb32Color
```

Representerar 32-bitars färg i ARGB-format, med 8 bitar per kanal (Alpha, Red, Green, Blue). Stöder transparens. Utformad för att vara användbar för (men inte begränsad till) CSS‑operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Argb32Color(int alpha, int red, int green, int blue)](#Argb32Color-int-int-int-int-) | Privat konstruktor, initierar ARGB-kanaler. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [EMPTY](#EMPTY) |  |
| [TRANSPARENT](#TRANSPARENT) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [toInternal()](#toInternal--) |  |
| [fromInternal(Argb32Color color)](#fromInternal-com.groupdocs.htmlcss.drawing.Argb32Color-) |  |
| [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) |  |
| [fromArgb(int argb)](#fromArgb-int-) |  |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) |  |
| [fromSingleValueRgb(int value)](#fromSingleValueRgb-int-) |  |
| [getValue()](#getValue--) |  |
| [getAlpha()](#getAlpha--) |  |
| [getAlphaFraction()](#getAlphaFraction--) |  |
| [getRed()](#getRed--) |  |
| [getGreen()](#getGreen--) |  |
| [getBlue()](#getBlue--) |  |
| [getArgbValue()](#getArgbValue--) |  |
| [isEmpty()](#isEmpty--) |  |
| [isDefault()](#isDefault--) |  |
| [isFullyTransparent()](#isFullyTransparent--) |  |
| [isFullyOpaque()](#isFullyOpaque--) |  |
| [isTranslucent()](#isTranslucent--) |  |
| [getBrightness()](#getBrightness--) |  |
| [getHue()](#getHue--) |  |
| [getSaturation()](#getSaturation--) |  |
| [toArgb()](#toArgb--) |  |
| [toRGBA()](#toRGBA--) |  |
| [toRGB()](#toRGB--) |  |
| [toHexRGBA()](#toHexRGBA--) |  |
| [toHexRGB()](#toHexRGB--) |  |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Argb32Color other)](#equals-com.groupdocs.viewer.drawing.Argb32Color-) |  |
| [equals(Rgb24Color other)](#equals-com.groupdocs.viewer.drawing.Rgb24Color-) |  |
| [toRgb24Color()](#toRgb24Color--) |  |
| [fromRgb24Color(Rgb24Color rgbColor)](#fromRgb24Color-com.groupdocs.viewer.drawing.Rgb24Color-) |  |
### Argb32Color(int alpha, int red, int green, int blue) {#Argb32Color-int-int-int-int-}
```
public Argb32Color(int alpha, int red, int green, int blue)
```


Privat konstruktor, initierar ARGB-kanaler.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | int |  |
| red | int |  |
| green | int |  |
| blue | int |  |

### EMPTY {#EMPTY}
```
public static final Argb32Color EMPTY
```


### TRANSPARENT {#TRANSPARENT}
```
public static final Argb32Color TRANSPARENT
```


### toInternal() {#toInternal--}
```
public Argb32Color toInternal()
```




**Returns:**
[Argb32Color](../../com.groupdocs.htmlcss.drawing/argb32color)
### fromInternal(Argb32Color color) {#fromInternal-com.groupdocs.htmlcss.drawing.Argb32Color-}
```
public static Argb32Color fromInternal(Argb32Color color)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| färg | com.groupdocs.htmlcss.drawing.Argb32Color |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static Argb32Color fromRgba(int red, int green, int blue, int alpha)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Argb32Color fromRgb(int red, int green, int blue)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### getAlpha() {#getAlpha--}
```
public int getAlpha()
```




**Returns:**
int
### getAlphaFraction() {#getAlphaFraction--}
```
public double getAlphaFraction()
```




**Returns:**
double
### getRed() {#getRed--}
```
public int getRed()
```




**Returns:**
int
### getGreen() {#getGreen--}
```
public int getGreen()
```




**Returns:**
int
### getBlue() {#getBlue--}
```
public int getBlue()
```




**Returns:**
int
### getArgbValue() {#getArgbValue--}
```
public int getArgbValue()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean
### isDefault() {#isDefault--}
```
public boolean isDefault()
```




**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public boolean isFullyTransparent()
```




**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public boolean isFullyOpaque()
```




**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public boolean isTranslucent()
```




**Returns:**
boolean
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```




**Returns:**
float
### getHue() {#getHue--}
```
public float getHue()
```




**Returns:**
float
### getSaturation() {#getSaturation--}
```
public float getSaturation()
```




**Returns:**
float
### toArgb() {#toArgb--}
```
public int toArgb()
```




**Returns:**
int
### toRGBA() {#toRGBA--}
```
public String toRGBA()
```




**Returns:**
java.lang.String
### toRGB() {#toRGB--}
```
public String toRGB()
```




**Returns:**
java.lang.String
### toHexRGBA() {#toHexRGBA--}
```
public String toHexRGBA()
```




**Returns:**
java.lang.String
### toHexRGB() {#toHexRGB--}
```
public String toHexRGB()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Argb32Color](../../com.groupdocs.viewer.drawing/argb32color) |  |

**Returns:**
boolean
### equals(Rgb24Color other) {#equals-com.groupdocs.viewer.drawing.Rgb24Color-}
```
public boolean equals(Rgb24Color other)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) |  |

**Returns:**
boolean
### toRgb24Color() {#toRgb24Color--}
```
public Rgb24Color toRgb24Color()
```




**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### fromRgb24Color(Rgb24Color rgbColor) {#fromRgb24Color-com.groupdocs.viewer.drawing.Rgb24Color-}
```
public static Argb32Color fromRgb24Color(Rgb24Color rgbColor)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgbColor | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) |  |

**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
