---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering documents into HTML format.
type: docs
weight: 15
url: /java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Provides options for rendering documents into HTML format.
## Methods

| Method | Description |
| --- | --- |
| [getImageMaxWidth()](#getImageMaxWidth--) | Max width of an output image in pixels. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Max width of an output image in pixels. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Max height of an output image in pixels. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Max height of an output image in pixels. |
| [getImageWidth()](#getImageWidth--) | The width of the output image in pixels. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | The width of the output image in pixels. |
| [getImageHeight()](#getImageHeight--) | The height of an output image in pixels. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | The height of an output image in pixels. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class. |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) |  |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources. |
| [forExternalResources()](#forExternalResources--) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class. |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class. |
| [isRenderResponsive()](#isRenderResponsive--) | Enables responsive rendering; Responsive web-pages render well on a devices with different screen size. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Enables responsive rendering; Responsive web-pages render well on a devices with different screen size. |
| [isMinify()](#isMinify--) | Enables HTML content and HTML resources minification. |
| [setMinify(boolean value)](#setMinify-boolean-) | Enables HTML content and HTML resources minification. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Enables HTML content will be rendered to single page |
| [isRenderToSinglePage()](#isRenderToSinglePage--) |  |
| [isExcludeFonts()](#isExcludeFonts--) | When enabled prevents adding any fonts into HTML document. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | When enabled prevents adding any fonts into HTML document. |
| [getFontsToExclude()](#getFontsToExclude--) | The list of font names, to exclude from HTML document. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | The list of font names, to exclude from HTML document. |
| [isEmbedResources()](#isEmbedResources--) |  |
| [isExternalResources()](#isExternalResources--) |  |
| [isForPrinting()](#isForPrinting--) | Indicates whether to optimize output HTML for printing. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Indicates whether to optimize output HTML for printing. |
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

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - New instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | The method that releases stream created by method assigned to delegate that passed to createPageStream parameter. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - New instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory which implements methods for creating and releasing output page stream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - New instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class.

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | The method that instantiates stream used to write output page data. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | The method that releases stream created by createPageStream method. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | The method that creates URL for HTML resource. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - New instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) |  |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) |  |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) |  |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) |  |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) |  |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | The factory which implements methods for creating and releasing output page stream. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | The factory which implements methods that are required for creating resource URL, instantiating and releasing output HTML resource stream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - New instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class.

--------------------

This constructor initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)

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


Initializes new instance of [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | The resource file path format e.g. 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | The resource URL format e.g. 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Enables responsive rendering; Responsive web-pages render well on a devices with different screen size.

**Returns:**
boolean
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Enables responsive rendering; Responsive web-pages render well on a devices with different screen size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Enables HTML content and HTML resources minification.

**Returns:**
boolean
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Enables HTML content and HTML resources minification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Enables HTML content will be rendered to single page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```




**Returns:**
boolean
### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


When enabled prevents adding any fonts into HTML document.

**Returns:**
boolean
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


When enabled prevents adding any fonts into HTML document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


The list of font names, to exclude from HTML document.

--------------------

This option is supported for presentations only. The fonts that are added into HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option, lets you find compromise, between stability and output size. Include the font names that are popular and installed into most systems.
Please note, this property is active only when  ExcludeFonts (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) options is disabled.

**Returns:**
java.util.List<java.lang.String>
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


The list of font names, to exclude from HTML document.

--------------------

This option is supported for presentations only. The fonts that are added into HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option, lets you find compromise, between stability and output size. Include the font names that are popular and installed into most systems. Please note, this property is active only when  ExcludeFonts (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) options is disabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> |  |

### isEmbedResources() {#isEmbedResources--}
```
public final boolean isEmbedResources()
```




**Returns:**
boolean
### isExternalResources() {#isExternalResources--}
```
public final boolean isExternalResources()
```




**Returns:**
boolean
### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Indicates whether to optimize output HTML for printing.

**Returns:**
boolean
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Indicates whether to optimize output HTML for printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

