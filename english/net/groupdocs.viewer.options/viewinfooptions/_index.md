---
title: ViewInfoOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Provides options used for retrieving information about view.
type: docs
weight: 550
url: /net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Provides options used for retrieving information about view.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Default font to be used when particular font used in document can't be found. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Indicates that text extraction is enabled. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Image height (for rendering to PNG/JPG only) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Max height of the output image (for rendering to PNG/JPG only) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Max width of the output image (for rendering to PNG/JPG only) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The MS Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF documents view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation processing documents view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Enables rendering comments. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files splitting to pages options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files processing documents view options. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Image width (for rendering to PNG/JPG only) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents. |

## Methods

| Name | Description |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class based on [`HtmlViewOptions`](../htmlviewoptions) object. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class based on [`JpgViewOptions`](../jpgviewoptions) object. |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class based on [`PdfViewOptions`](../pdfviewoptions) object. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initializes new instance of [`ViewInfoOptions`](../viewinfooptions) class based on [`PngViewOptions`](../pngviewoptions) object. |

### See Also

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
