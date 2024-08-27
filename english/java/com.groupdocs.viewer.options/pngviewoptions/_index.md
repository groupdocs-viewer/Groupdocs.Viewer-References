---
title: PngViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into PNG format.
type: docs
weight: 25
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

The PngViewOptions class encapsulates additional settings and parameters that can be used to control the rendering of documents into PNG format in the GroupDocs.Viewer component.

Example usage:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Constructors

| Constructor | Description |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes a new instance of the  PngViewOptions  class. |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes a new instance of the  PngViewOptions  class. |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes a new instance of the  PngViewOptions  class. |
| [PngViewOptions()](#PngViewOptions--) | Initializes new instance of  PngViewOptions  class. |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initializes a new instance of the  PngViewOptions  class. |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initializes a new instance of the  PngViewOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Returns the maximum width of an output image in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Sets the maximum width of an output image in pixels. |
| [getMaxHeight()](#getMaxHeight--) | Returns the maximum height of an output image in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Sets the maximum height of an output image in pixels. |
| [isExtractText()](#isExtractText--) | Determines whether text extraction is enabled. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Enables or disables text extraction. |
| [getWidth()](#getWidth--) | Returns the width of the output image in pixels. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of the output image in pixels. |
| [getHeight()](#getHeight--) | Returns the height of the output image in pixels. |
| [setHeight(int value)](#setHeight-int-) | Sets the height of the output image in pixels. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Retrieves the callback for estimating the saving progress of a document. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Sets the callback for estimating the saving progress of a document. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initializes a new instance of the  PngViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write the output page data. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes a new instance of the  PngViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write the output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases the stream created by the method assigned to the createPageStream parameter. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initializes a new instance of the  PngViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory that implements methods for creating and releasing the output page stream. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initializes new instance of  PngViewOptions  class.

This constructor initializes new instance of  PngViewOptions  with "p\_\{0\}.png" as file path format for the output files. The output files will be placed into current working directory of the application. For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initializes a new instance of the  PngViewOptions  class.

For example, if the file path format is 'page\_\{0\}.png', the output files will be named as 'page\_1.png', 'page\_2.png', and so on, based on the page number.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format, e.g., 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initializes a new instance of the  PngViewOptions  class.

For example, if the file path format is 'page\_\{0\}.png', the output files will be named as 'page\_1.png', 'page\_2.png', and so on, based on the page number. For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | The file path format, e.g., 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Returns the maximum width of an output image in pixels.

Use this property to set the maximum output image width (in pixels). For code example, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - the maximum width of the output image.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Sets the maximum width of an output image in pixels.

Use this property to set the maximum output image width (in pixels). For code example, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | The maximum width of the output image. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Returns the maximum height of an output image in pixels.

Use this property to set the maximum output image height (in pixels). For code example, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - the maximum height of the output image.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Sets the maximum height of an output image in pixels.

Use this property to set the maximum output image height (in pixels). For code example, see the [documentation][]. If you set the  property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int | The maximum height of the output image. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Determines whether text extraction is enabled.

This option might be useful when you want to add a selectable text layer over the image. Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  if text extraction is enabled,  false  otherwise.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Enables or disables text extraction.

This option might be useful when you want to add a selectable text layer over the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable text extraction,  false  to disable it. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Returns the width of the output image in pixels.

Use this property to set the output image width (in pixels). For code example, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - the width of the output image.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of the output image in pixels.

Use this property to set the output image width (in pixels). For code example, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the output image. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Returns the height of the output image in pixels.

Use this property to set the output image height (in pixels). For code example, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - the height of the output image.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of the output image in pixels.

Use this property to set the output image height (in pixels). For code example, see the [documentation][]. If you set this property, the  property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the output image. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Retrieves the callback for estimating the saving progress of a document.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - the callback to estimate the document saving progress.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Sets the callback for estimating the saving progress of a document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | The callback to estimate the document saving progress. |

