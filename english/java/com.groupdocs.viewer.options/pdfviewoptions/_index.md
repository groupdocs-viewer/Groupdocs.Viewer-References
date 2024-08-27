---
title: PdfViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into PDF format.
type: docs
weight: 23
url: /java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Provides options for rendering documents into PDF format.

The PdfViewOptions class encapsulates additional settings and parameters that can be used to control the rendering of documents into PDF format in the GroupDocs.Viewer component. For details, see the [documentation][].

Example usage:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initializes a new instance of the  PdfViewOptions  class. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initializes a new instance of the  PdfViewOptions  class. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initializes a new instance of the  PdfViewOptions  class. |
| [PdfViewOptions()](#PdfViewOptions--) | Initializes a new instance of the  PdfViewOptions  class with default settings. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initializes a new instance of the  PdfViewOptions  class. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initializes a new instance of the  PdfViewOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Reduce output PDF file size applying optimization techniques with different options. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Reduce output PDF file size applying optimization techniques with different options. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Retrieves the maximum width of an output image in pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Sets the maximum width of an output image in pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Retrieves the maximum height of an output image in pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Sets the maximum height of an output image in pixels. |
| [getImageWidth()](#getImageWidth--) | Retrieves the width of the output image in pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Sets the width of the output image in pixels. |
| [getImageHeight()](#getImageHeight--) | Retrieves the height of the output image in pixels. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Sets the height of the output image in pixels. |
| [getSecurity()](#getSecurity--) | Retrieves the security options for the output PDF document. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Sets the security options for the output PDF document. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Retrieves the callback used to estimate the progress of saving a Words or Email document. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Sets the callback used to estimate the progress of saving a Words or Email document. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initializes a new instance of the  PdfViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initializes a new instance of the  PdfViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | The method used to instantiate the stream for writing the output file data. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | The method used to release the stream created by the  createFileStream  method. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initializes a new instance of the  PdfViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | The factory that implements methods for creating and releasing the output file stream. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initializes a new instance of the  PdfViewOptions  class with default settings.

This constructor creates a new  PdfViewOptions  object with "output.pdf" as the file path format for the output file. The output file will be placed into the current working directory of the application. For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initializes a new instance of the  PdfViewOptions  class.

This constructor creates a new  PdfViewOptions  object with the specified  outputFilePath  parameter representing the path for the output PDF file. For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFilePath | java.lang.String | The path for the output PDF file. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initializes a new instance of the  PdfViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | The path for the output PDF file. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Reduce output PDF file size applying optimization techniques with different options.

This option is supported for any input file formats which are supported for conversion to PDF: [Supported document formats][] For details and code samples, see this [page][] and its children.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Reduce output PDF file size applying optimization techniques with different options.

This option is supported for any input file formats which are supported for conversion to PDF: [Supported document formats][] For details and code samples, see this [page][] and its children.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions object or null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Retrieves the maximum width of an output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the maximum output image width (in pixels). GroupDocs.Viewer applies this property when rendering a single image to PDF. For details, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - the maximum width of the output image in pixels.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Sets the maximum width of an output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the maximum output image width (in pixels). GroupDocs.Viewer applies this property when rendering a single image to PDF. For details, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxWidth | int | The maximum width of the output image in pixels. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Retrieves the maximum height of an output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the maximum output image height (in pixels). GroupDocs.Viewer applies this property when rendering a single image to PDF. For details, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - the maximum height of the output image in pixels.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Sets the maximum height of an output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the maximum output image height (in pixels). GroupDocs.Viewer applies this property when rendering a single image to HTML only. For details, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxHeight | int | The maximum height of the output image in pixels. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Retrieves the width of the output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the output image width (in pixels). GroupDocs.Viewer applies this property when rendering a single image to PDF. For details, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - the width of the output image in pixels.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Sets the width of the output image in pixels. This parameter applies only when converting a single image PDF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageWidth | int | The width of the output image in pixels. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Retrieves the height of the output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the output image height (in pixels). GroupDocs.Viewer applies this property when rendering a single image to HTML only. For details, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - the height of the output image in pixels.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Sets the height of the output image in pixels. This parameter applies only when converting a single image to HTML.

Use this property to set the output image height (in pixels). GroupDocs.Viewer applies this property when rendering a single image to HTML only. For details, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageHeight | int | The height of the output image in pixels. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Retrieves the security options for the output PDF document.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Sets the security options for the output PDF document.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | The security options for the output PDF document. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Retrieves the callback used to estimate the progress of saving a Words or Email document.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - the callback to estimate the document saving progress.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Sets the callback used to estimate the progress of saving a Words or Email document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | The callback to estimate the document saving progress. |

