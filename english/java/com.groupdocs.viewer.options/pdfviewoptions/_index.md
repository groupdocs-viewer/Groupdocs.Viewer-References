---
title: PdfViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into PDF format.
type: docs
weight: 21
url: /java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Provides options for rendering documents into PDF format.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
| [PdfViewOptions()](#PdfViewOptions--) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getJpgQuality()](#getJpgQuality--) | The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90. |
| [setJpgQuality(int value)](#setJpgQuality-int-) | The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Max width of an output image in pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Max width of an output image in pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Max height of an output image in pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Max height of an output image in pixels. |
| [getImageWidth()](#getImageWidth--) | The width of the output image in pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | The width of the output image in pixels. |
| [getImageHeight()](#getImageHeight--) | The height of an output image in pixels. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | The height of an output image in pixels. |
| [getSecurity()](#getSecurity--) | The output PDF document security options. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | The output PDF document security options. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Callback to estimate Words or Email document saving progress |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Callback to estimate Words or Email document saving progress |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | The method that instantiates stream used to write output file data. |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | The method that instantiates stream used to write output file data. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | The method that releases stream created by method assigned to delegate that passed to createFileStream parameter. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | The factory which implements methods for creating and releasing output file stream. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

--------------------

This constructor initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) with "output.pdf" as file path format for the output file. The output file will be placed into current working directory of the application.

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFilePath | java.lang.String | The path for output PDF file. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initializes new instance of [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | The path for output PDF file. |

### getJpgQuality() {#getJpgQuality--}
```
public final int getJpgQuality()
```


The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90.

**Returns:**
int
### setJpgQuality(int value) {#setJpgQuality-int-}
```
public final void setJpgQuality(int value)
```


The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Max width of an output image in pixels. (When converting single image to HTML only)

**Returns:**
int
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Max width of an output image in pixels. (When converting single image to HTML only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxWidth | int |  |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Max height of an output image in pixels. (When converting single image to HTML only)

**Returns:**
int
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Max height of an output image in pixels. (When converting single image to HTML only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxHeight | int |  |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


The width of the output image in pixels. (When converting single image to HTML only)

**Returns:**
int
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


The width of the output image in pixels. (When converting single image to HTML only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageWidth | int |  |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


The height of an output image in pixels. (When converting single image to HTML only)

**Returns:**
int
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


The height of an output image in pixels. (When converting single image to HTML only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageHeight | int |  |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


The output PDF document security options.

**Returns:**
[Security](../../com.groupdocs.viewer.options/security)
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


The output PDF document security options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) |  |

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

