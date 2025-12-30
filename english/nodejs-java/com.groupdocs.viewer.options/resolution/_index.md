---
title: Resolution
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides option to set resolution for images  output document.
type: docs
weight: 44
url: /nodejs-java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Provides option to set resolution for images : output document.
## Fields

| Field | Description |
| --- | --- |
| [DPI_330](#DPI-330) | Good quality for high-definition (HD) displays. |
| [DPI_220](#DPI-220) | Excellent quality on most printers and screens. |
| [DPI_150](#DPI-150) | Good for web pages and projectors. |
| [DPI_96](#DPI-96) | Good for web pages and projectors. |
| [DPI_72](#DPI-72) | Default compression level. |
| [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Default compression level - as the document. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getValue()](#getValue--) | Quality DPI. |
| [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Get Aspose.Slides pictures resolution from options Resolution class. |
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Good quality for high-definition (HD) displays.

### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Excellent quality on most printers and screens.

### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Good for web pages and projectors.

### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Good for web pages and projectors.

### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Default compression level.

### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Default compression level - as the document.

### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Quality DPI.

**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Get Aspose.Slides pictures resolution from options Resolution class.

**Returns:**
int
