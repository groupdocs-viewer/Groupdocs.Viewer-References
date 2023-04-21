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
## Fields

| Field | Description |
| --- | --- |
| [OPTIONS](#OPTIONS) |  |
## Methods

| Method | Description |
| --- | --- |
| [isExtractText()](#isExtractText--) | Indicates that text extraction is enabled. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Indicates that text extraction is enabled. |
| [getMaxWidth()](#getMaxWidth--) | Max width of the output image (for rendering to PNG/JPG only) |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Max width of the output image (for rendering to PNG/JPG only) |
| [getMaxHeight()](#getMaxHeight--) | Max height of the output image (for rendering to PNG/JPG only) |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Max height of the output image (for rendering to PNG/JPG only) |
| [getWidth()](#getWidth--) | Image width (for rendering to PNG/JPG only) |
| [setWidth(int width)](#setWidth-int-) | Image width (for rendering to PNG/JPG only) |
| [getHeight()](#getHeight--) | Image height (for rendering to PNG/JPG only) |
| [setHeight(int height)](#setHeight-int-) | Image height (for rendering to PNG/JPG only) |
| [forHtmlView()](#forHtmlView--) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML. |
| [forJpgView()](#forJpgView--) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG. |
| [forPngView()](#forPngView--) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object. |
### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indicates that text extraction is enabled.

**Returns:**
boolean
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Indicates that text extraction is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean |  |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Max width of the output image (for rendering to PNG/JPG only)

**Returns:**
int
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Max width of the output image (for rendering to PNG/JPG only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int |  |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Max height of the output image (for rendering to PNG/JPG only)

**Returns:**
int
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Max height of the output image (for rendering to PNG/JPG only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Image width (for rendering to PNG/JPG only)

**Returns:**
int
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Image width (for rendering to PNG/JPG only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Image height (for rendering to PNG/JPG only)

**Returns:**
int
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Image height (for rendering to PNG/JPG only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | int |  |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderSinglePage | boolean | Enables HTML content will be rendered to single page. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into JPG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean | Enables text extraction. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class to retrieve information about view when rendering into PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extractText | boolean | Enables text extraction. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | The HTML view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | The PNG view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initializes new instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class based on [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | The JPG view options. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
