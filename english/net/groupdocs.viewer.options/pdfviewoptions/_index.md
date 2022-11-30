---
title: PdfViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Provides options for rendering documents into PDF format.
type: docs
weight: 390
url: /net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Provides options for rendering documents into PDF format.

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initializes new instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initializes new instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initializes new instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initializes new instance of [`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initializes new instance of [`PdfViewOptions`](../pdfviewoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Default font to be used when particular font used in document can't be found. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | The height of an output image in pixels. (When converting single image to HTML only) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Max height of an output image in pixels. (When converting single image to HTML only) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Max width of an output image in pixels. (When converting single image to HTML only) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | The width of the output image in pixels. (When converting single image to HTML only) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | The quality of the JPG images contained by output PDF document; Valid values are between 1 and 100; Default value is 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The MS Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF documents view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation processing documents view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Enables rendering comments. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | The output PDF document security options. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files splitting to pages options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files processing documents view options. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | The text watermark applied to each page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Web documents. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | This rendering options enables you to customize the appearance of the output HTML/PDF/PNG/JPEG when rendering Word documents. |

## Methods

| Name | Description |
| --- | --- |
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
