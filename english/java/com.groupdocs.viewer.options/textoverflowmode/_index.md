---
title: TextOverflowMode
second_title: GroupDocs.Viewer for Java API Reference
description: Defines text overflow mode for rendering spreadsheet documents into HTML.
type: docs
weight: 42
url: /java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Defines text overflow mode for rendering spreadsheet documents into HTML.

The TextOverflowMode enum represents different modes for handling text overflow in the GroupDocs.Viewer component. It provides a set of predefined options that can be used to control how text is displayed when it exceeds the available space in cells during the rendering of spreadsheet documents into HTML.

Example usage:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [OVERLAY](#OVERLAY) | Overlay next cells even if they are not empty. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Overlay next cells only if they are empty. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Expand columns to fit the text. |
| [HIDE_TEXT](#HIDE-TEXT) | Hide the overflow text. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Overlay next cells even if they are not empty. This mode allows the text to overflow into the adjacent cells, regardless of their content.

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Overlay next cells only if they are empty. This mode allows the text to overflow into the adjacent cells only if those cells are empty.

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Expand columns to fit the text. This mode automatically adjusts the width of the columns to accommodate the overflowing text.

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Hide the overflow text. This mode hides the overflowing text, preventing it from being displayed.

### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
