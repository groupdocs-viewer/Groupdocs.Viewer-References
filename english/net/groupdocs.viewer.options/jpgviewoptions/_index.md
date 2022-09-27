---
title: JpgViewOptions
second_title: GroupDocs.Viewer for .NET API Reference
description: Provides options for rendering documents into JPG format.
type: docs
weight: 360
url: /net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

Provides options for rendering documents into JPG format.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Initializes new instance of [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Initializes new instance of [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Initializes new instance of [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Initializes new instance of [`JpgViewOptions`](../jpgviewoptions) class. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initializes new instance of [`JpgViewOptions`](../jpgviewoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | The archive files view options. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | The CAD drawing view options. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Default font to be used when particular font used in document can't be found. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | The email messages view options. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Enables text extraction. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | The height of an output image in pixels. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Mail storage data files view options. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Max height of an output image in pixels. |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Max width of an output image in pixels. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | The MS Outlook data files view options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | The PDF documents view options. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | The presentation processing documents view options. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | The project management files view options. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Quality of the output image; Valid values are between 1 and 100; Default value is 90. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Enables rendering comments. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Enables rendering of hidden pages. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Enables rendering notes. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | The spreadsheet files view options. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Text files splitting to pages options. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | The Visio files processing documents view options. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | The text watermark applied to each page. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | The width of the output image in pixels. |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
