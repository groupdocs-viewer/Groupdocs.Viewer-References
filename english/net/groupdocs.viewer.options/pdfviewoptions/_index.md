---
title: PdfViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Contains options for rendering documents into PDF format. For details see the documentationhttps//docs.groupdocs.com/viewer/net/renderingtopdf/.
type: docs
weight: 570
url: /net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Contains options for rendering documents into PDF format. For details, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initializes an instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initializes an instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initializes an instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initializes an instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initializes an instance of [`PdfViewOptions`](../pdfviewoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Sets the default font for a document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Sets the height of an output image (in pixels). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Sets the maximum height of an output image (in pixels). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Sets the maximum width of an output image (in pixels). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Sets the width of an output image (in pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The Microsoft Outlook data files view options. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Reduces output PDF file size by applying optimization techniques with different options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF document view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation files view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Disables rendering comments when set to `true`. By default is `false` — all comments are displayed. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Sets the output PDF document security options. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files view options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files view options. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | The text watermark to be applied to each page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | The Web files view options. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | The Word processing files view options. |

## Methods

| Name | Description |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applies the clockwise rotation to a page. |

## Fields

| Name | Description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | The page rotation. |

### See Also

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
