---
title: "Image2DFormat"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει μια μορφή εικόνας 2D — ραστερ ή διανύσματος."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer.drawing/image2dformat/
---
**Inheritance:**
java.lang.Object
```
public final class Image2DFormat
```

Αναπαριστά μορφή 2D εικόνας \\u2014 raster ή vector.

## Πεδία

| Πεδίο | Περιγραφή |
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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [toInternal()](#toInternal--) |  |
| [fromInternal(Image2DFormat format)](#fromInternal-com.groupdocs.htmlcss.drawing.Image2DFormat-) |  |
| [getName()](#getName--) |  |
| [getFormalName()](#getFormalName--) |  |
| [isVector()](#isVector--) |  |
| [getFileExtension()](#getFileExtension--) |  |
| [getMimeCode()](#getMimeCode--) |  |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) |  |
| [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) |  |
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


### toInternal() {#toInternal--}
```
public Image2DFormat toInternal()
```




**Returns:**
[Image2DFormat](../../com.groupdocs.htmlcss.drawing/image2dformat)
### fromInternal(Image2DFormat format) {#fromInternal-com.groupdocs.htmlcss.drawing.Image2DFormat-}
```
public static Image2DFormat fromInternal(Image2DFormat format)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | com.groupdocs.htmlcss.drawing.Image2DFormat |  |

**Returns:**
[Image2DFormat](../../com.groupdocs.viewer.drawing/image2dformat)
### getName() {#getName--}
```
public String getName()
```




**Returns:**
java.lang.String
### getFormalName() {#getFormalName--}
```
public String getFormalName()
```




**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public boolean isVector()
```




**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public String getFileExtension()
```




**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public String getMimeCode()
```




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
| Παράμετρος | Τύπος | Περιγραφή |
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




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | java.lang.String |  |

**Returns:**
[Image2DFormat](../../com.groupdocs.viewer.drawing/image2dformat)
### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static Image2DFormat parseFromMime(String mimeCode)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mimeCode | java.lang.String |  |

**Returns:**
[Image2DFormat](../../com.groupdocs.viewer.drawing/image2dformat)
