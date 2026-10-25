---
title: "Rgb24Color"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет 24-битный цвет в формате RGB с 8 битами на каждый канал Красный, Зеленый, Синий."
type: docs
weight: 12
url: /ru/java/com.groupdocs.viewer.drawing/rgb24color/
---
**Inheritance:**
java.lang.Object
```
public class Rgb24Color
```

Представляет 24-битный цвет в формате RGB, с 8 битами на каждый канал (Красный, Зеленый, Синий). Не поддерживает прозрачность. Предназначен для использования в (но не ограничивается) операциях CSS. Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Rgb24Color(int r, int g, int b)](#Rgb24Color-int-int-int-) |  |
## Методы

| Метод | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| цвет | com.groupdocs.htmlcss.drawing.Rgb24Color |  |

**Returns:**
[Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color)
### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static Rgb24Color fromRgb(int red, int green, int blue)
```




**Parameters:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
