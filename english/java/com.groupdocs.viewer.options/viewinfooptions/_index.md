---
title: ViewInfoOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options used for retrieving information about view.
type: docs
weight: 31
url: /java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Provides options used for retrieving information about view.

The ViewInfoOptions class encapsulates additional settings and parameters that can be used to retrieve information about a view in the GroupDocs.Viewer component.

Example usage:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Methods

| Method | Description |
| --- | --- |
| [isExtractText()](#isExtractText--) | Indicates whether text extraction is enabled. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Sets the flag indicating whether text extraction is enabled. |
| [getMaxWidth()](#getMaxWidth--) | Returns the maximum width of the output image for rendering to PNG/JPG. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Sets the maximum width of the output image for rendering to PNG/JPG. |
| [getMaxHeight()](#getMaxHeight--) | Returns the maximum height of the output image for rendering to PNG/JPG. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Sets the maximum height of the output image for rendering to PNG/JPG. |
| [getWidth()](#getWidth--) | Returns the width of the image for rendering to PNG/JPG. |
| [setWidth(int width)](#setWidth-int-) | Sets the width of the image for rendering to PNG/JPG. |
| [getHeight()](#getHeight--) | Returns the height of the image for rendering to PNG/JPG. |
| [setHeight(int height)](#setHeight-int-) | Sets the height of the image for rendering to PNG/JPG. |
| [forHtmlView()](#forHtmlView--) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into HTML. |
| [forJpgView()](#forJpgView--) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into JPG. |
| [forPngView()](#forPngView--) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into PNG. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initializes a new instance of the  ViewInfoOptions  class based on the [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initializes a new instance of the  ViewInfoOptions  class based on the [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initializes a new instance of the  ViewInfoOptions  class based on the [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indicates whether text extraction is enabled.

**Returns:**
boolean - True if text extraction is enabled, false otherwise.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Sets the flag indicating whether text extraction is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean | True to enable text extraction, false to disable. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Returns the maximum width of the output image for rendering to PNG/JPG.

**Returns:**
int - the maximum width of the output image.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Sets the maximum width of the output image for rendering to PNG/JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | The maximum width of the output image. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Returns the maximum height of the output image for rendering to PNG/JPG.

**Returns:**
int - the maximum height of the output image.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Sets the maximum height of the output image for rendering to PNG/JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int | The maximum height of the output image. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Returns the width of the image for rendering to PNG/JPG.

**Returns:**
int - the width of the image.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Sets the width of the image for rendering to PNG/JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the image. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Returns the height of the image for rendering to PNG/JPG.

**Returns:**
int - the height of the image.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Sets the height of the image for rendering to PNG/JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | int | The height of the image. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into HTML.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean | Enables HTML content to be rendered on a single page. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean | Enables text extraction. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initializes a new instance of the  ViewInfoOptions  class to retrieve information about the view when rendering into PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean | Enables text extraction. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initializes a new instance of the  ViewInfoOptions  class based on the [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | The HTML view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initializes a new instance of the  ViewInfoOptions  class based on the [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | The PNG view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initializes a new instance of the  ViewInfoOptions  class based on the [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | The JPG view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
