---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into HTML format.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Provides options for rendering documents into HTML format.

The HtmlViewOptions class encapsulates additional settings and parameters that can be used to control the rendering of documents into HTML format in the GroupDocs.Viewer component.

Example usage:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Methods

| Method | Description |
| --- | --- |
| [getImageMaxWidth()](#getImageMaxWidth--) | Returns the maximum width of an output image in pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Sets the maximum width of an output image in pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Gets the maximum height of an output image in pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Sets the maximum height of an output image in pixels. |
| [getImageWidth()](#getImageWidth--) | Gets the width of the output image in pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Sets the width of the output image in pixels. |
| [getImageHeight()](#getImageHeight--) | Gets the height of the output image in pixels when converting a single image to HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Sets the height of the output image in pixels when converting a single image to HTML. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Initializes a new instance of the  HtmlViewOptions  class. |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initializes a new instance of the  HtmlViewOptions  class. |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initializes a new instance of the  HtmlViewOptions  class. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources. |
| [forExternalResources()](#forExternalResources--) | Initializes new instance of  HtmlViewOptions  class. |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the  HtmlViewOptions  class. |
| [isRenderResponsive()](#isRenderResponsive--) | Determines whether responsive rendering is enabled. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Sets whether responsive rendering is enabled. |
| [isMinify()](#isMinify--) | Checks if HTML content and HTML resources minification is enabled. |
| [setMinify(boolean value)](#setMinify-boolean-) | Sets whether HTML content and HTML resources minification is enabled. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Sets whether HTML content will be rendered to a single page. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Determines whether HTML content will be rendered to a single page. |
| [isExcludeFonts()](#isExcludeFonts--) | Determines whether to exclude fonts from the HTML document. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Sets whether to exclude fonts from the HTML document. |
| [getFontsToExclude()](#getFontsToExclude--) | Retrieves the list of font names to exclude from the HTML document. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Sets the list of font names to exclude from the HTML document. |
| [isForPrinting()](#isForPrinting--) | Checks if the output HTML should be optimized for printing. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Sets whether the output HTML should be optimized for printing. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Retrieves the callback used to estimate the saving progress of a Words or Email document. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Sets the callback used to estimate the saving progress of a Words or Email document. |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Returns the maximum width of an output image in pixels.

**Note:** This value is used when converting a single image to HTML.

**Returns:**
int - the maximum width of an output image.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Sets the maximum width of an output image in pixels.

**Note:** This value is used when converting a single image to HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxWidth | int | The maximum width of an output image. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Gets the maximum height of an output image in pixels.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.

**Returns:**
int - the maximum height of an output image.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Sets the maximum height of an output image in pixels.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageMaxHeight | int | The maximum height of an output image. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Gets the width of the output image in pixels.

***Note:** This value is applicable only when converting a single image to HTML.*

**Returns:**
int - the width of the output image.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Sets the width of the output image in pixels.

***Note:** This value is applicable only when converting a single image to HTML.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageWidth | int | The width of the output image. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Gets the height of the output image in pixels when converting a single image to HTML.

**Returns:**
int - the height of the output image in pixels.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Sets the height of the output image in pixels when converting a single image to HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageHeight | int | The height of the output image in pixels. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates a stream used to write output page data. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates a stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases the stream created by the method assigned to the  createPageStream  parameter. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory that implements methods for creating and releasing the output page stream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initializes a new instance of the  HtmlViewOptions  class.

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initializes a new instance of the  HtmlViewOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format, e.g., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initializes a new instance of the  HtmlViewOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | The file path format, e.g., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | The method that releases the stream created by the  createPageStream  method. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | The method that creates the URL for the HTML resource. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates the stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | The method that instantiates the stream used to write output HTML resource data. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | The method that creates the URL for the HTML resource. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases the stream created by the  createPageStream  method. |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | The method that releases the stream created by the  createResourceStream  method. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initializes a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory that implements methods for creating and releasing the output page stream. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | The factory that implements methods for creating resource URLs and instantiating/releasing the output HTML resource stream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - A new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initializes new instance of  HtmlViewOptions  class.

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

The output files will be placed into current working directory of the application.

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initializes a new instance of the  HtmlViewOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format, e.g., 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | The resource file path format, e.g., 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | The resource URL format, e.g., 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Determines whether responsive rendering is enabled. Responsive web pages render well on devices with different screen sizes.

**Returns:**
boolean -  true  if responsive rendering is enabled,  false  otherwise.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Sets whether responsive rendering is enabled. Responsive web pages render well on devices with different screen sizes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable responsive rendering,  false  to disable it. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Checks if HTML content and HTML resources minification is enabled.

**Returns:**
boolean -  true  if minification is enabled,  false  otherwise.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Sets whether HTML content and HTML resources minification is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable minification,  false  to disable. |

### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Sets whether HTML content will be rendered to a single page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean |  true  if HTML content should be rendered to a single page,  false  otherwise. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Determines whether HTML content will be rendered to a single page.

**Returns:**
boolean -  true  if HTML content will be rendered to a single page,  false  otherwise.
### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Determines whether to exclude fonts from the HTML document.

**Returns:**
boolean -  true  if fonts should be excluded,  false  otherwise.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Sets whether to exclude fonts from the HTML document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to exclude fonts,  false  otherwise. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Retrieves the list of font names to exclude from the HTML document.

This option is supported for presentations only. Including fonts in the HTML document improves the stability of the output view but increases the rendering result's size. Use this option to find a compromise between stability and output size. Include font names that are popular and installed on most systems.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.*

**Returns:**
java.util.List<java.lang.String> - the list of font names to exclude from the HTML document.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Sets the list of font names to exclude from the HTML document.

This option is supported for presentations only. Including fonts in the HTML document improves the stability of the output view but increases the rendering result's size. Use this option to find a compromise between stability and output size. Include font names that are popular and installed on most systems.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | The list of font names to exclude from the HTML document. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Checks if the output HTML should be optimized for printing.

**Returns:**
boolean -  true  if the output HTML should be optimized for printing,  false  otherwise.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Sets whether the output HTML should be optimized for printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to optimize the output HTML for printing,  false  otherwise. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Retrieves the callback used to estimate the saving progress of a Words or Email document.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - the callback used to estimate the document saving progress.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Sets the callback used to estimate the saving progress of a Words or Email document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | The callback used to estimate the document saving progress. |

