---
title: PngViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into PNG format.
type: docs
weight: 23
url: /java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Provides options for rendering documents into PNG format.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class. |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes new instance of PngViewOptions class. |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class. |
| [PngViewOptions()](#PngViewOptions--) | Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class. |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Max width of an output image in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Max width of an output image in pixels. |
| [getMaxHeight()](#getMaxHeight--) | Max height of an output image in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Max height of an output image in pixels. |
| [isExtractText()](#isExtractText--) | Enables text extraction. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Enables text extraction. |
| [getWidth()](#getWidth--) | The width of the output image in pixels. |
| [setWidth(int value)](#setWidth-int-) | The width of the output image in pixels. |
| [getHeight()](#getHeight--) | The height of an output image in pixels. |
| [setHeight(int value)](#setHeight-int-) | The height of an output image in pixels. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Callback to estimate Words or Email document saving progress |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Callback to estimate Words or Email document saving progress |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes new instance of PngViewOptions class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases stream created by method assigned to delegate that passed to createPageStream parameter. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory which implements methods for creating and releasing output page stream. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class.

--------------------

This constructor initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) with "p\_\{0\}.png" as file path format for the output files. The output files will be placed into current working directory of the application.

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initializes new instance of [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'page\_\{0\}.png'. |

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

