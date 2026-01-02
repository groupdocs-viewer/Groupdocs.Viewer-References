---
title: Position
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Defines watermark position.
type: docs
weight: 43
url: /nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Defines watermark position.

The Position enum represents different positions for a watermark in the GroupDocs.Viewer component. It provides a set of predefined positions that can be used to specify the placement of a watermark on a document or image during the rendering process.

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
## Fields

| Field | Description |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | The diagonal position. |
| [TOP_LEFT](#TOP-LEFT) | The top left position. |
| [TOP_CENTER](#TOP-CENTER) | The top center position. |
| [TOP_RIGHT](#TOP-RIGHT) | The top right position. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | The bottom left position. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | The bottom center position. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | The bottom right position. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


The diagonal position. This position represents a diagonal alignment or placement.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


The top left position. This position represents the top left corner alignment or placement.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


The top center position. This position represents the top center alignment or placement.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


The top right position. This position represents the top right corner alignment or placement.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


The bottom left position. This position represents the bottom left corner alignment or placement.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


The bottom center position. This position represents the bottom center alignment or placement.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


The bottom right position. This position represents the bottom right corner alignment or placement.

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
