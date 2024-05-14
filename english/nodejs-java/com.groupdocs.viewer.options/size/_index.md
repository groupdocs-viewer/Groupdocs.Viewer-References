---
title: Size
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Watermark size.
type: docs
weight: 28
url: /nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Watermark size.

The Size class represents the size of a watermark in the GroupDocs.Viewer component. It provides options to specify the dimensions of the watermark, such as width and height.

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
| [Size(byte relativeSize)](#Size-byte-) | Initializes a new instance of the  Size  class. |
## Fields

| Field | Description |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Represents the maximum size of watermark text that fits the page. |
| [HALF_SIZE](#HALF-SIZE) | Represents half of the maximum size of watermark text that fits the page. |
| [ONE_THIRD](#ONE-THIRD) | Represents one third of the maximum size of watermark text that fits the page. |
## Methods

| Method | Description |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Returns the watermark text size in percentages in relation to the page width. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initializes a new instance of the  Size  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relativeSize | byte | The size in percentages in relation to the page size. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Represents the maximum size of watermark text that fits the page.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Represents half of the maximum size of watermark text that fits the page.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Represents one third of the maximum size of watermark text that fits the page.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Returns the watermark text size in percentages in relation to the page width.

**Returns:**
byte - the watermark text size in percentages.
