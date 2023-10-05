---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/htmlviewoptions/
---

## HtmlViewOptions class

 Provides options for rendering documents into HTML format.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| CREATE_PAGE_STREAM | createPageStream |  |
| FILE_PATH_FORMAT | filePathFormat |  |


## Functions

| Name | Description |
| --- | --- |
| [forEmbeddedResources](forembeddedresources)([CreatePageStream](../createpagestream)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with embedded resources. |
| [forEmbeddedResources](forembeddedresources)([CreatePageStream](../createpagestream), [ReleasePageStream](../releasepagestream)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with embedded resources. |
| [forEmbeddedResources](forembeddedresources)([PageStreamFactory](../pagestreamfactory)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with embedded resources. |
| [forEmbeddedResources](forembeddedresources)() | Initializes new instance of HtmlViewOptions class. |
| [forEmbeddedResources](forembeddedresources)(String) | Initializes new instance of HtmlViewOptions class. |
| [forEmbeddedResources](forembeddedresources)(Path) | Initializes new instance of HtmlViewOptions class. |
| [forExternalResources](forexternalresources)([CreatePageStream](../createpagestream), [CreateResourceStream](../createresourcestream), [CreateResourceUrl](../createresourceurl)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with external resources. |
| [forExternalResources](forexternalresources)([CreatePageStream](../createpagestream), [CreateResourceStream](../createresourcestream), [CreateResourceUrl](../createresourceurl),  [ReleasePageStream](../releasepagestream), [ReleaseResourceStream](../releaseresourcestream)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with external resources. |
| [forExternalResources](forexternalresources)([PageStreamFactory](../pagestreamfactory), [ResourceStreamFactory](../resourcestreamfactory)) | Initializes new instance of HtmlViewOptions class for rendering into HTML with external resources. |
| [forExternalResources](forexternalresources)() | Initializes new instance of HtmlViewOptions class. This constructor initializes new instance of HtmlViewOptions - with "p_{0}.html" as file path format for the output HTML files; - with "p_{0}_{1}" as file path format for the output HTML-resource files; - with "p_{0}_{1}" as URL format for HTML-resources; The output files will be placed into current working directory of the application. |
| [forExternalResources](forexternalresources)(String, String, String) | Initializes new instance of HtmlViewOptions class. |
| [getDocumentSavingCallback](getdocumentsavingcallback)() | Callback to estimate Words or Email document saving progress |
| [getFontsToExclude](getfontstoexclude)() | The list of font names, to exclude from HTML document. This option is supported for presentations only. The fonts that are added into HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option, lets you find compromise, between stability and output size. Include the font names that are popular and installed into most systems. Please note, this property is active only when ExcludeFonts( #isExcludeFonts()/ #setExcludeFonts(boolean)) options is disabled. |
| [getImageHeight](getimageheight)() | The height of an output image in pixels. (When converting single image to HTML only) |
| [getImageMaxHeight](getimagemaxheight)() | Max height of an output image in pixels. (When converting single image to HTML only) |
| [getImageMaxWidth](getimagemaxwidth)() | Max width of an output image in pixels. (When converting single image to HTML only) |
| [getImageWidth](getimagewidth)() | The width of the output image in pixels. (When converting single image to HTML only) |
| [getPageStreamFactory](getpagestreamfactory)() |  |
| [getResourceStreamFactory](getresourcestreamfactory)() |  |
| [isEmbedResources](isembedresources)() |  |
| [isExcludeFonts](isexcludefonts)() | When enabled prevents adding any fonts into HTML document. |
| [isExternalResources](isexternalresources)() |  |
| [isForPrinting](isforprinting)() | Indicates whether to optimize output HTML for printing. |
| [isMinify](isminify)() | Enables HTML content and HTML resources minification. |
| [isRenderResponsive](isrenderresponsive)() | Enables responsive rendering; Responsive web-pages render well on a devices with different screen size. |
| [isRenderSinglePage](isrendersinglepage)() | Enables HTML content will be rendered to single page |
| [isRenderToSinglePage](isrendertosinglepage)() | Enables HTML content will be rendered to single page |
| [setDocumentSavingCallback](setdocumentsavingcallback)(IDocumentSavingCallback) | Callback to estimate Words or Email document saving progress |
| [setExcludeFonts](setexcludefonts)(boolean) | When enabled prevents adding any fonts into HTML document. |
| [setFontsToExclude](setfontstoexclude)(java.util.List<java.lang.String>) | The list of font names, to exclude from HTML document. This option is supported for presentations only. The fonts that are added into HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option, lets you find compromise, between stability and output size. Include the font names that are popular and installed into most systems. Please note, this property is active only when ExcludeFonts( #isExcludeFonts()/ #setExcludeFonts(boolean)) options is disabled. |
| [setForPrinting](setforprinting)(boolean) | Indicates whether to optimize output HTML for printing. |
| [setImageHeight](setimageheight)(int) | The height of an output image in pixels. (When converting single image to HTML only) |
| [setImageMaxHeight](setimagemaxheight)(int) | Max height of an output image in pixels. (When converting single image to HTML only) |
| [setImageMaxWidth](setimagemaxwidth)(int) | Max width of an output image in pixels. (When converting single image to HTML only) |
| [setImageWidth](setimagewidth)(int) | The width of the output image in pixels. (When converting single image to HTML only) |
| [setMinify](setminify)(boolean) | Enables HTML content and HTML resources minification. |
| [setRenderResponsive](setrenderresponsive)(boolean) | Enables responsive rendering; Responsive web-pages render well on a devices with different screen size. |
| [setRenderSinglePage](setrendersinglepage)(boolean) | Enables HTML content will be rendered to single page |
| [setRenderToSinglePage](setrendertosinglepage)(boolean) | Enables HTML content will be rendered to single page |
