---
title: JpgViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Provides options for rendering documents into JPG format. For details see this pagehttps//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ and its children.
type: docs
weight: 330
url: /net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

Provides options for rendering documents into JPG format. For details, see this [page](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) and its children.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Initializes an instance of the [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Initializes an instance of the [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Initializes an instance of the [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Initializes an instance of the [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initializes an instance of the [`JpgViewOptions`](../jpgviewoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Sets the default font for a document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Enables text extraction. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Sets the height of an output image (in pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Sets the maximum height of an output image (in pixels). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Sets the maximum width of an output image (in pixels). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The Microsoft Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF document view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation files view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Sets the quality of the output image. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Enables rendering comments. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files view options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files view options. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | The text watermark to be applied to each page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | The Web files view options. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Sets the width of the output image (in pixels). |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
