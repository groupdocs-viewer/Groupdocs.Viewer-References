---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa color de 24 bits en formato RGB con 8 bits por cada canal Rojo Verde Azul."
type: docs
weight: 12
url: /es/java/com.groupdocs.viewer.drawing/rgb24color/
---
**Inheritance:**
java.lang.Object
```
public class Rgb24Color
```

Representa color de 24 bits en formato RGB, con 8 bits por cada canal (Rojo, Verde, Azul). No admite transparencia. Diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Rgb24Color(int r, int g, int b)](#Rgb24Color-int-int-int-) |  |
## Métodos

| Método | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | com.groupdocs.htmlcss.drawing.Rgb24Color |  |

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Rgb24Color fromRgb(int red, int green, int blue)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rojo | int |  |
| verde | int |  |
| azul | int |  |

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
| Parámetro | Tipo | Descripción |
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
