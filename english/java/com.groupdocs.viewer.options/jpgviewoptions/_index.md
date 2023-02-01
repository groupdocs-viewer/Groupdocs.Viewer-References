---
title: JpgViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into JPG format.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Provides options for rendering documents into JPG format.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class. |
| [JpgViewOptions()](#JpgViewOptions--) | Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Max width of an output image in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Max width of an output image in pixels. |
| [getMaxHeight()](#getMaxHeight--) | Max height of an output image in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Max height of an output image in pixels. |
| [getQuality()](#getQuality--) | Quality of the output image; Valid values are between 1 and 100; Default value is 90. |
| [setQuality(byte value)](#setQuality-byte-) | Quality of the output image; Valid values are between 1 and 100; Default value is 90. |
| [isExtractText()](#isExtractText--) | Enables text extraction. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Enables text extraction. |
| [getWidth()](#getWidth--) | The width of the output image in pixels. |
| [setWidth(int value)](#setWidth-int-) | The width of the output image in pixels. |
| [getHeight()](#getHeight--) | The height of an output image in pixels. |
| [setHeight(int value)](#setHeight-int-) | The height of an output image in pixels. |
| [getPageStreamFactory()](#getPageStreamFactory--) | The factory which implements methods for creating and releasing output page stream. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Callback to estimate Words or Email document saving progress |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Callback to estimate Words or Email document saving progress |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases stream created by method assigned to delegate that passed to createPageStream parameter. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory which implements methods for creating and releasing output page stream. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class.

--------------------

This constructor initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) with "p\_\{0\}.jpg" as file path format for the output files. The output files will be placed into current working directory of the application.

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initializes new instance of [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'page\_\{0\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Max width of an output image in pixels.

**Returns:**
int
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Max width of an output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int |  |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Max height of an output image in pixels.

**Returns:**
int
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Max height of an output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int |  |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Quality of the output image; Valid values are between 1 and 100; Default value is 90.

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Quality of the output image; Valid values are between 1 and 100; Default value is 90.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Enables text extraction.

--------------------

This option might be useful when you want to add selectable text layer over the image.

**Returns:**
boolean
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Enables text extraction.

--------------------

This option might be useful when you want to add selectable text layer over the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


The width of the output image in pixels.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


The width of the output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


The height of an output image in pixels.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


The height of an output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


The factory which implements methods for creating and releasing output page stream.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory)
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Callback to estimate Words or Email document saving progress

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - Callback to estimate document saving progress
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Callback to estimate Words or Email document saving progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Callback to estimate document saving progress |

