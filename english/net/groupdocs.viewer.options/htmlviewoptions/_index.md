---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Provides options for rendering documents into HTML format.
type: docs
weight: 300
url: /net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Provides options for rendering documents into HTML format.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Default font to be used when particular font used in document can't be found. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | When enabled prevents adding any fonts into HTML document. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | The list of font names, to exclude from HTML document. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Indicates whether to optimize output HTML for printing. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | The height of an output image in pixels. (When converting single image to HTML only) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Max height of an output image in pixels. (When converting single image to HTML only) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Max width of an output image in pixels. (When converting single image to HTML only) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | The width of the output image in pixels. (When converting single image to HTML only) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Enables HTML content and HTML resources minification. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The MS Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF documents view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation processing documents view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Enables rendering comments. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Enables responsive rendering; Responsive web-pages render well on a devices with different screen size. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Enables HTML content will be rendered to single page |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files splitting to pages options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files processing documents view options. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | The text watermark applied to each page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents. |

## Methods

| Name | Description |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with embedded resources. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with embedded resources. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with embedded resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with external resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with external resources. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initializes new instance of [`HtmlViewOptions`](../htmlviewoptions) class for rendering into HTML with external resources. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applies clockwise rotation to the page. |

## Fields

| Name | Description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | The page rotations. |

### See Also

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
