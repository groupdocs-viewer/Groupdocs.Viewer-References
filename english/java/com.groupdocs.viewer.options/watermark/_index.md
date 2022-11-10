---
title: Watermark
second_title: GroupDocs.Viewer for Java API Reference
description: Represents text watermark.
type: docs
weight: 33
url: /java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Represents text watermark.
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Initializes new instance of [Watermark](../../com.groupdocs.viewer.options/watermark) class. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | The watermark text. |
| [getColor()](#getColor--) | The watermark color. |
| [setColor(Color value)](#setColor-java.awt.Color-) | The watermark color. |
| [getPosition()](#getPosition--) | The watermark position. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | The watermark position. |
| [getSize()](#getSize--) | The watermark size. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | The watermark size. |
| [getFontName()](#getFontName--) | The font name used for the watermark. |
| [setFontName(String value)](#setFontName-java.lang.String-) | The font name used for the watermark. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initializes new instance of [Watermark](../../com.groupdocs.viewer.options/watermark) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Watermark text. |

### getText() {#getText--}
```
public final String getText()
```


The watermark text.

**Returns:**
java.lang.String - The watermark text.
### getColor() {#getColor--}
```
public final Color getColor()
```


The watermark color. Default value is Color\#getRed().getRed().

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


The watermark color. Default value is Color\#getRed().getRed().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


The watermark position. Default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - The watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


The watermark position. Default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | The watermark position. |

### getSize() {#getSize--}
```
public final Size getSize()
```


The watermark size. Default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).

**Returns:**
[Size](../../com.groupdocs.viewer.options/size)
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


The watermark size. Default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) |  |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


The font name used for the watermark.

**Returns:**
java.lang.String
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


The font name used for the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

