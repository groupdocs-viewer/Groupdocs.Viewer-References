---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till JPG-format. För detaljer se denna sidahttps//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ och dess underliggande sidor."
type: docs
weight: 350
url: /sv/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

Tillhandahåller alternativ för rendering av dokument till JPG-format. För detaljer, se denna [sida](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) och dess underavsnitt.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | Initierar en instans av klassen [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | Initierar en instans av klassen [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | Initierar en instans av klassen [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | Initierar en instans av klassen [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initierar en instans av klassen [`JpgViewOptions`](../jpgviewoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativ för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Visningsalternativ för CAD-ritningar. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ställer in standardteckensnittet för ett dokument. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visningsalternativ för e-postmeddelanden. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | Aktiverar textutvinning. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | Ställer in höjden på en utdata bild (i pixlar). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visningsalternativ för e-postlagringsdatafiler. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | Ställer in den maximala höjden på en utdata bild (i pixlar). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | Ställer in den maximala bredden på en utdata bild (i pixlar). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativ för Microsoft Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativ för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visningsalternativ för presentationsfiler. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visningsalternativ för projektledningsfiler. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | Ställer in kvaliteten på den utgående bilden. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Inaktiverar rendering av kommentarer när den är satt till `true`. Som standard är den `false` — alla kommentarer visas. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiverar rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar och annotationer för vissa format |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativ för kalkylbladsfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Visningsalternativ för textfiler. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visningsalternativ för Visio-filer. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textvattenstämpeln som ska tillämpas på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Visningsalternativ för webbfil. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | Ställer in bredden på den utgående bilden (i pixlar). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Visningsalternativ för ordbehandlingsfiler. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Tillämpar medursrotation på en sida. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sidrotationen. |

### Se även

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
