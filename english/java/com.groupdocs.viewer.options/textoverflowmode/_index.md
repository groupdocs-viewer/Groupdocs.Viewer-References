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
## Fields

| Field | Description |
| --- | --- |
| [OVERLAY](#OVERLAY) | Overlay next cells even they are not empty. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Overlay next cells only if they are empty. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Expand columns to fit the text. |
| [HIDE_TEXT](#HIDE-TEXT) | Hide overflow text. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Overlay next cells even they are not empty.

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Overlay next cells only if they are empty.

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Expand columns to fit the text.

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Hide overflow text.

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
