---
title: PdfOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering PDF documents.
type: docs
weight: 22
url: /java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Provides options for rendering PDF documents.

The PdfOptions class encapsulates various settings and parameters that can be used to control the rendering of PDF documents in the GroupDocs.Viewer component. For details, see the [documentation][].

Example usage:

```

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initializes a new instance of  PdfOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Determines whether the text from the source is rendered as an image in HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Sets whether the text from the source is rendered as an image in HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Checks if character grouping is disabled to maintain maximum precision during character positioning when rendering the page. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Sets the option to disable character grouping, ensuring maximum precision during character positioning when rendering the page. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Checks whether rendering of text and graphics should follow the z-order in the original PDF document when rendering into HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Enables or disables rendering of text and graphics according to the z-order in the original PDF document when rendering into HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Determines whether font hinting is enabled. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Enables font hinting. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Enables rendering of pages with the same size in pixels as the page size in the source PDF document. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Enables rendering of pages with the same size in pixels as the page size in the source PDF document. |
| [getImageQuality()](#getImageQuality--) | Retrieves the output image quality for image resources when rendering into HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Sets the output image quality for image resources when rendering into HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF is a fixed format so all of the elements have a specific place on a page. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF is a fixed format so all of the elements have a specific place on a page. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Enable this option to wrap each image in the output HTML document in SVG tag to improve output quality. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Enable this option to wrap each image in the output HTML document in SVG tag to improve output quality. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Disable any license restrictions for all fonts in current XPS/OXPS document. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Set the flag to disable any license restrictions for all fonts in current XPS/OXPS document. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initializes a new instance of  PdfOptions  class.

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Determines whether the text from the source is rendered as an image in HTML.

When this option is set to  true , the text is rendered as an image in the output HTML. Enable this option to make the text unselectable or to fix character rendering and make the HTML look like PDF. This option is supported when rendering into HTML.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if the text is rendered as an image in HTML,  false  otherwise.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Sets whether the text from the source is rendered as an image in HTML.

When this option is set to  true , the text is rendered as an image in the output HTML. Enable this option to make the text unselectable or to fix character rendering and make the HTML look like PDF. This option is supported when rendering into HTML.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderTextAsImage | boolean |  true  to render the text as an image in HTML,  false  otherwise. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Checks if character grouping is disabled to maintain maximum precision during character positioning when rendering the page. When this option is enabled, the characters are rendered without any grouping, which ensures maximum precision.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean -  true  if character grouping is disabled,  false  otherwise.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Sets the option to disable character grouping, ensuring maximum precision during character positioning when rendering the page. When this option is enabled by setting the value to  true , character grouping is disabled, which ensures maximum precision.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to disable character grouping,  false  to enable it. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Checks whether rendering of text and graphics should follow the z-order in the original PDF document when rendering into HTML. When this option is enabled by returning  true , text and graphics are rendered according to their z-order in the original PDF document.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean -  true  if layered rendering is enabled,  false  otherwise.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Enables or disables rendering of text and graphics according to the z-order in the original PDF document when rendering into HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable layered rendering,  false  to disable it. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Determines whether font hinting is enabled. Font hinting adjusts the display of an outline font. This option is supported only for TrueType (TTF) fonts when used in the source document.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean -  true  if font hinting is enabled,  false  otherwise.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Enables font hinting. Font hinting adjusts the display of an outline font and is supported only for TrueType (TTF) fonts when used in the source document.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable font hinting,  false  to disable it. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Enables rendering of pages with the same size in pixels as the page size in the source PDF document.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean -  true  if the option is enabled,  false  otherwise.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Enables rendering of pages with the same size in pixels as the page size in the source PDF document.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderOriginalPageSize | boolean |  true  to enable rendering with the original page size,  false  otherwise. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Retrieves the output image quality for image resources when rendering into HTML. The default value is Low.

When this option is set to true, GroupDocs.Viewer renders text as an image in the HTML output. This makes the text unselectable and enhances character rendering, ensuring a PDF-like appearance in HTML. The default value is false. This option is available for rendering to HTML. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Sets the output image quality for image resources when rendering into HTML. The default value is Low.

When this option is set to true, GroupDocs.Viewer renders text as an image in the HTML output. This makes the text unselectable and enhances character rendering, ensuring a PDF-like appearance in HTML. The default value is false. This option is available for rendering to HTML. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | The output image quality for image resources when rendering into HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF is a fixed format so all of the elements have a specific place on a page. To ensure that the output HTML looks the same as the source PDF the documents are rendered to HTML with a fixed layout by default. When rendering with fixed layout the output HTML has fixed size so the elements will stay on the same place regardless of window size. To render to HTML with fluid layout set this property to false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Example usage:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true if it is fixed layout
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF is a fixed format so all of the elements have a specific place on a page. To ensure that the output HTML looks the same as the source PDF the documents are rendered to HTML with a fixed layout by default. When rendering with fixed layout the output HTML has fixed size so the elements will stay on the same place regardless of window size. To render to HTML with fluid layout set this property to false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Example usage:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixedLayout | boolean | true if it is fixed layout |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Enable this option to wrap each image in the output HTML document in SVG tag to improve output quality.

This option is supported when rendering [PDF and Page Layout file formats][] to HTML with embedded and external resources.

By default, when rendering to PDF and Page Layout files, all the images are rendered as one PNG image. The rendered PNG image is used as the background for the output HTML document.

Learn more:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  if images are wrapped in SVG,  false  otherwise.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Enable this option to wrap each image in the output HTML document in SVG tag to improve output quality.

This option is supported when rendering [PDF and Page Layout file formats][] to HTML with embedded and external resources.

By default, when rendering to PDF and Page Layout files, all the images are rendered as one PNG image. The rendered PNG image is used as the background for the output HTML document.

Learn more:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wrapImagesInSvg | boolean |  true  if images should be wrapped in SVG,  false  otherwise. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Disable any license restrictions for all fonts in current XPS/OXPS document.

Many operations with font can't be executed if these operations are prohibited by the license of this font. For example, some font can't be embedded into a PDF document if the license rules disable embedding for this font. Be careful when using this flag. When it is set, it means that the person who sets this flag takes all responsibility for possible license/law violations on themselves. So they take it on their own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. For code example, see the [documentation][].

Example usage:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Set the flag to disable any license restrictions for all fonts in current XPS/OXPS document.

Many operations with font can't be executed if these operations are prohibited by the license of this font. For example, some font can't be embedded into a PDF document if the license rules disable embedding for this font. Be careful when using this flag. When it is set, it means that the person who sets this flag takes all responsibility for possible license/law violations on themselves. So they take it on their own risk. It's strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. By default false. For code example, see the [documentation][].

Example usage:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

