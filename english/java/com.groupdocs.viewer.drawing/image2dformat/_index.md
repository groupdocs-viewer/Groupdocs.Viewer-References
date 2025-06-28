---
title: Image2DFormat
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a 2D image format u2014 raster or vector.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.drawing/image2dformat/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.htmlcss.resources.IResourceType
```
public final class Image2DFormat implements IResourceType
```

Represents a 2D image format \\u2014 raster or vector.
## Fields

| Field | Description |
| --- | --- |
| [UNDEFINED](#UNDEFINED) |  |
| [JPEG](#JPEG) |  |
| [PNG](#PNG) |  |
| [BMP](#BMP) |  |
| [GIF](#GIF) |  |
| [TIFF](#TIFF) |  |
| [ICON](#ICON) |  |
| [SVG](#SVG) |  |
| [WMF](#WMF) |  |
| [EMF](#EMF) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns a formal name of this image format. |
| [getFormalName()](#getFormalName--) | Returns a formal name of this image format. |
| [isVector()](#isVector--) | Indicates whether this format is vector (true) or raster (false). |
| [getFileExtension()](#getFileExtension--) | Returns lowercase file extension (without dot) for this format. |
| [getMimeCode()](#getMimeCode--) | MIME code of the image format. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returns Image2DFormat based on file extension (with or without dot). |
| [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Returns Image2DFormat based on MIME type string. |
### UNDEFINED {#UNDEFINED}
```
public static final Image2DFormat UNDEFINED
```


### JPEG {#JPEG}
```
public static final Image2DFormat JPEG
```


### PNG {#PNG}
```
public static final Image2DFormat PNG
```


### BMP {#BMP}
```
public static final Image2DFormat BMP
```


### GIF {#GIF}
```
public static final Image2DFormat GIF
```


### TIFF {#TIFF}
```
public static final Image2DFormat TIFF
```


### ICON {#ICON}
```
public static final Image2DFormat ICON
```


### SVG {#SVG}
```
public static final Image2DFormat SVG
```


### WMF {#WMF}
```
public static final Image2DFormat WMF
```


### EMF {#EMF}
```
public static final Image2DFormat EMF
```


### getName() {#getName--}
```
public String getName()
```


Returns a formal name of this image format. Never returns null.

**Returns:**
java.lang.String
### getFormalName() {#getFormalName--}
```
public String getFormalName()
```


Returns a formal name of this image format. Never returns null.

**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public boolean isVector()
```


Indicates whether this format is vector (true) or raster (false).

**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public String getFileExtension()
```


Returns lowercase file extension (without dot) for this format.

**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public String getMimeCode()
```


MIME code of the image format.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static Image2DFormat parseFromFilenameWithExtension(String filename)
```


Returns Image2DFormat based on file extension (with or without dot).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String |  |

**Returns:**
[Image2DFormat](../../com.groupdocs.viewer.drawing/image2dformat)
### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static Image2DFormat parseFromMime(String mimeCode)
```


Returns Image2DFormat based on MIME type string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mimeCode | java.lang.String |  |

**Returns:**
[Image2DFormat](../../com.groupdocs.viewer.drawing/image2dformat)
