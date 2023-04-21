---
title: PdfOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering PDF documents.
type: docs
weight: 21
url: /java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Provides options for rendering PDF documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initializes new instance of [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Disables chars grouping to keep maximum precision during chars positioning when rendering the page. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Enables font hinting. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Enables font hinting. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. |
| [setRenderOriginalPageSize(boolean mRenderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. |
| [getImageQuality()](#getImageQuality--) | Specifies output image quality for image resources when rendering into HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Specifies output image quality for image resources when rendering into HTML. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initializes new instance of [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) class.

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false.  This option is supported when rendering into HTML.

**Returns:**
boolean
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false.  This option is supported when rendering into HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderTextAsImage | boolean |  |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

When this option is set to true, the text is rendered as an image in the output HTML. Enable this option to make text unselectable or to fix characters rendering and make HTML look like PDF. The default value is false.  This option is supported when rendering into HTML.

/\*\*

Disables chars grouping to keep maximum precision during chars positioning when rendering the page.

**Returns:**
boolean
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Disables chars grouping to keep maximum precision during chars positioning when rendering the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML.

--------------------

By default text and graphics are rendered into HTML as a single layer.

**Returns:**
boolean
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Enables rendering of text and graphics according to z-order in original PDF document when rendering into HTML.

--------------------

By default text and graphics are rendered into HTML as a single layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Enables font hinting. The font hinting adjusts the display of an outline font. Supported only for TTF fonts when these fonts are used in source document.

--------------------

This option is supported when rendering into PNG or JPG formats.

**Returns:**
boolean
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Enables font hinting. The font hinting adjusts the display of an outline font. Supported only for TTF fonts when these fonts are used in source document.

--------------------

This option is supported when rendering into PNG or JPG formats.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. By default GroupDocs.Viewer calculates output image page size for better rendering quality.

**Returns:**
boolean - This option is supported when rendering into PNG or JPG formats.
### setRenderOriginalPageSize(boolean mRenderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean mRenderOriginalPageSize)
```


When this option enabled the output pages will have the same size in pixels as page size in a source PDF document. By default GroupDocs.Viewer calculates output image page size for better rendering quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mRenderOriginalPageSize | boolean | This option is supported when rendering into PNG or JPG formats. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Specifies output image quality for image resources when rendering into HTML. The default value is Low.

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - Specifies output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Specifies output image quality for image resources when rendering into HTML. The default value is Low.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Specifies output image quality for image resources when rendering into HTML. |

