---
title: Size
second_title: GroupDocs.Viewer for Java API Reference
description: Watermark size.
type: docs
weight: 27
url: /java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Watermark size.
## Constructors

| Constructor | Description |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Initializes new instance of [Size](../../com.groupdocs.viewer.options/size) class. |
## Fields

| Field | Description |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | The maximum size of watermark text that fits page. |
| [HALF_SIZE](#HALF-SIZE) | The half of the maximum size of watermark text that fits page. |
| [ONE_THIRD](#ONE-THIRD) | The one third of the maximum size of watermark text that fits page. |
## Methods

| Method | Description |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | The watermark text size in percentages in relation to page width. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initializes new instance of [Size](../../com.groupdocs.viewer.options/size) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relativeSize | byte | The size in percents in relation to page size. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


The maximum size of watermark text that fits page.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


The half of the maximum size of watermark text that fits page.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


The one third of the maximum size of watermark text that fits page.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


The watermark text size in percentages in relation to page width. Valid values are between 1 and 100.

**Returns:**
byte
