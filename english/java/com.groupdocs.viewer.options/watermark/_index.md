---
title: Watermark
second_title: GroupDocs.Viewer for Java API Reference
description: Represents text watermark.
type: docs
weight: 34
url: /java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Represents text watermark.

The Watermark class represents a text watermark in the GroupDocs.Viewer component. It is used to define and apply a watermark to the rendered output of documents.

Example usage:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Initializes a new instance of the  Watermark  class. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Returns the watermark text. |
| [getColor()](#getColor--) | Returns the watermark color. |
| [getColorAsHex()](#getColorAsHex--) | Returns the watermark color in hex format. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Sets the watermark color. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Sets the watermark color. |
| [getPosition()](#getPosition--) | Returns the watermark position. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Sets the watermark position. |
| [getSize()](#getSize--) | Returns the watermark size. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Sets the watermark size. |
| [getFontName()](#getFontName--) | Returns the font name used for the watermark. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Sets the font name used for the watermark. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initializes a new instance of the  Watermark  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The watermark text. |

### getText() {#getText--}
```
public final String getText()
```


Returns the watermark text. This method retrieves the text of the watermark applied to the document.

**Returns:**
java.lang.String - the watermark text.
### getColor() {#getColor--}
```
public final Color getColor()
```


Returns the watermark color. This method retrieves the color of the watermark applied to the document.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - the watermark color.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Returns the watermark color in hex format. This method retrieves the color of the watermark applied to the document.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - the watermark color in hex format.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Sets the watermark color. This method sets the color of the watermark applied to the document.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color | The watermark color to set. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Sets the watermark color. This method sets the color of the watermark applied to the document.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorName | java.lang.String | The watermark color to set. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Returns the watermark position. This method returns the position of the watermark applied to the document.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Sets the watermark position. This method sets the position of the watermark applied to the document.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | The watermark position. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Returns the watermark size. This method retrieves the size of the watermark applied to the document.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Sets the watermark size. This method sets the size of the watermark to be applied to the document.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | The watermark size. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returns the font name used for the watermark.

**Returns:**
java.lang.String - the font name used for the watermark.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Sets the font name used for the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The font name used for the watermark. |

