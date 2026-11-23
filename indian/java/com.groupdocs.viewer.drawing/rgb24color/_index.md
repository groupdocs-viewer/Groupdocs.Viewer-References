---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "RGB फ़ॉर्मेट में 24-बिट रंग का प्रतिनिधित्व करता है, जिसमें प्रत्येक चैनल (लाल, हरा, नीला) के लिए 8 बिट्स होते हैं।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.viewer.drawing/rgb24color/
---
**Inheritance:**
java.lang.Object
```
public class Rgb24Color
```

RGB फ़ॉर्मेट में 24-बिट रंग का प्रतिनिधित्व करता है, जिसमें प्रत्येक चैनल (लाल, हरा, नीला) के लिए 8 बिट्स होते हैं। पारदर्शिता का समर्थन नहीं करता। (परंतु केवल CSS संचालन तक सीमित नहीं) उपयोगी होने के लिए डिज़ाइन किया गया है। अधिक देखें: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

## Constructors

| Constructor | विवरण |
| --- | --- |
| [Rgb24Color(int r, int g, int b)](#Rgb24Color-int-int-int-) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [toInternal()](#toInternal--) |  |
| [fromInternal(Rgb24Color color)](#fromInternal-com.groupdocs.htmlcss.drawing.Rgb24Color-) |  |
| [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) |  |
| [getR()](#getR--) |  |
| [getG()](#getG--) |  |
| [getB()](#getB--) |  |
| [isDefault()](#isDefault--) |  |
| [getBrightness()](#getBrightness--) |  |
| [getHue()](#getHue--) |  |
| [getSaturation()](#getSaturation--) |  |
| [toArgb()](#toArgb--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [toRGB()](#toRGB--) |  |
| [toHex()](#toHex--) |  |
| [toString()](#toString--) |  |
### Rgb24Color(int r, int g, int b) {#Rgb24Color-int-int-int-}
```
public Rgb24Color(int r, int g, int b)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### toInternal() {#toInternal--}
```
public Rgb24Color toInternal()
```




**Returns:**
[Rgb24Color](../../com.groupdocs.htmlcss.drawing/rgb24color)
### fromInternal(Rgb24Color color) {#fromInternal-com.groupdocs.htmlcss.drawing.Rgb24Color-}
```
public static Rgb24Color fromInternal(Rgb24Color color)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| color | com.groupdocs.htmlcss.drawing.Rgb24Color |  |

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Rgb24Color fromRgb(int red, int green, int blue)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| red | int |  |
| green | int |  |
| blue | int |  |

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### getR() {#getR--}
```
public int getR()
```




**Returns:**
int
### getG() {#getG--}
```
public int getG()
```




**Returns:**
int
### getB() {#getB--}
```
public int getB()
```




**Returns:**
int
### isDefault() {#isDefault--}
```
public boolean isDefault()
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### toRGB() {#toRGB--}
```
public String toRGB()
```




**Returns:**
java.lang.String
### toHex() {#toHex--}
```
public String toHex()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
