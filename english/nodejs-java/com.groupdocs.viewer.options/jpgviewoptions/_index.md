---
title: JpgViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering documents into JPG format.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Provides options for rendering documents into JPG format.

The JpgViewOptions class encapsulates additional settings and parameters that can be used to control the rendering of documents into JPG format in the GroupDocs.Viewer component.

Example usage:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## Constructors

| Constructor | Description |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes a new instance of the  JpgViewOptions  class. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes a new instance of the  JpgViewOptions  class. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes a new instance of the  JpgViewOptions  class. |
| [JpgViewOptions()](#JpgViewOptions--) | Initializes a new instance of  JpgViewOptions  with "p\_\{0\}.jpg" as the file path format for the output files. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initializes a new instance of the  JpgViewOptions  class. |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initializes a new instance of the  JpgViewOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Gets the maximum width of an output image in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Sets the maximum width of an output image in pixels. |
| [getMaxHeight()](#getMaxHeight--) | Gets the maximum height of an output image in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Sets the maximum height of an output image in pixels. |
| [getQuality()](#getQuality--) | Gets the quality of the output image. |
| [setQuality(byte value)](#setQuality-byte-) | Sets the quality of the output image. |
| [isExtractText()](#isExtractText--) | Enables text extraction. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Enables or disables text extraction. |
| [getWidth()](#getWidth--) | Gets the width of the output image in pixels. |
| [setWidth(int value)](#setWidth-int-) | Sets the width of the output image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the output image in pixels. |
| [setHeight(int value)](#setHeight-int-) | Sets the height of the output image in pixels. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Gets the factory that implements methods for creating and releasing the output page stream. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Gets the callback to estimate the saving progress of a Words or Email document. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Sets the callback to estimate the saving progress of a Words or Email document. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initializes a new instance of the  JpgViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write the output page data. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes a new instance of the  JpgViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write the output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases the stream created by the method assigned to the delegate passed to the  createPageStream  parameter. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initializes a new instance of the  JpgViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory that implements methods for creating and releasing the output page stream. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initializes a new instance of  JpgViewOptions  with "p\_\{0\}.jpg" as the file path format for the output files. The output files will be placed into the current working directory of the application.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initializes a new instance of the  JpgViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format, e.g., 'page\_\{0\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initializes a new instance of the  JpgViewOptions  class.

For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | The file path format, e.g., 'page\_\{0\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Gets the maximum width of an output image in pixels.

Use this property to set the maximum output image width (in pixels). For code example, see the [documentation][]. If you set the \#setWidth(int).setWidth(int) property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - the maximum width of an output image.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Sets the maximum width of an output image in pixels.

Use this property to set the maximum output image width (in pixels). For code example, see the [documentation][]. If you set the \#setWidth(int).setWidth(int) property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | The maximum width of an output image. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Gets the maximum height of an output image in pixels.

Use this property to set the maximum output image height (in pixels). For code example, see the [documentation][]. If you set the \#setHeight(int).setHeight(int) property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - the maximum height of an output image.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Sets the maximum height of an output image in pixels.

Use this property to set the maximum output image height (in pixels). For code example, see the [documentation][]. If you set the \#setHeight(int).setHeight(int) property, this property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int | The maximum height of an output image. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Gets the quality of the output image.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - the quality of the output image.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Sets the quality of the output image.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The quality of the output image. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Enables text extraction.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  if text extraction is enabled,  false  otherwise.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Enables or disables text extraction.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable text extraction,  false  to disable it. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the output image in pixels.

Use this property to set the output image width (in pixels). For code example, see the [documentation][]. If you set this property, the \#setMaxWidth(int).setMaxWidth(int) property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - the width of the output image.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Sets the width of the output image in pixels.

Use this property to set the output image width (in pixels). For code example, see the [documentation][]. If you set this property, the \#setMaxWidth(int).setMaxWidth(int) property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The width of the output image. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the output image in pixels.

Use this property to set the output image height (in pixels). For code example, see the [documentation][]. If you set this property, the \#setMaxHeight(int).setMaxHeight(int) property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - the height of the output image.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Sets the height of the output image in pixels.

Use this property to set the output image height (in pixels). For code example, see the [documentation][]. If you set this property, the \#setMaxHeight(int).setMaxHeight(int) property is ignored.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The height of the output image. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Gets the factory that implements methods for creating and releasing the output page stream.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Gets the callback to estimate the saving progress of a Words or Email document.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - the callback to estimate the document saving progress.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Sets the callback to estimate the saving progress of a Words or Email document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | The callback to estimate the document saving progress. |

