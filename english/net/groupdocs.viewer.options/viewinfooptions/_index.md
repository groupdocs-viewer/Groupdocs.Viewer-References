---
title: ViewInfoOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Contains options for retrieving information about view.
type: docs
weight: 700
url: /net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Contains options for retrieving information about view.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Sets the default font for a document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Enables text extraction. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | The height of the output image (in pixels, for rendering to PNG/JPG only). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Sets the maximum height of an output image (in pixels, for rendering to PNG/JPG only). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Sets the maximum width of an output image (in pixels, for rendering to PNG/JPG only). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The Microsoft Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF document view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation files view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Disables rendering comments when set to `true`. By default is `false` — all comments are displayed. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files view options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files view options. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | The Web files view options. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | The width of the output image (in pixels, for rendering to PNG/JPG only). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | The Word processing files view options. |

## Methods

| Name | Description |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class to retrieve information about view when rendering into PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class based on the [`HtmlViewOptions`](../htmlviewoptions) object. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class based on the [`JpgViewOptions`](../jpgviewoptions) object. |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class based on the [`PdfViewOptions`](../pdfviewoptions) object. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initializes an instance of the [`ViewInfoOptions`](../viewinfooptions) class based on the [`PngViewOptions`](../pngviewoptions) object. |

### See Also

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
