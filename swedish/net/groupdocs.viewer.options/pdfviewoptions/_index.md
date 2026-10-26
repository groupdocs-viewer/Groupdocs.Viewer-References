---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Innehåller alternativ för att rendera dokument till PDF-format. För detaljer se dokumentationenhttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /sv/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Innehåller alternativ för rendering av dokument till PDF-format. För detaljer, se [dokumentationen](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initierar en instans av [`PdfViewOptions`](../pdfviewoptions) klass. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initierar en instans av [`PdfViewOptions`](../pdfviewoptions) klass. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initierar en instans av [`PdfViewOptions`](../pdfviewoptions) klass. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initierar en instans av [`PdfViewOptions`](../pdfviewoptions) klass. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initierar en instans av [`PdfViewOptions`](../pdfviewoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativ för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Visningsalternativ för CAD-ritningar. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ställer in standardteckensnittet för ett dokument. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visningsalternativ för e-postmeddelanden. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Ställer in höjden på en utdata bild (i pixlar). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Ställer in den maximala höjden på en utdata bild (i pixlar). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Ställer in den maximala bredden på en utdata bild (i pixlar). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Ställer in bredden på en utdata bild (i pixlar). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visningsalternativ för e-postlagringsdatafiler. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativ för Microsoft Outlook-datafiler. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Minskar storleken på utdata‑PDF‑filen genom att tillämpa optimeringstekniker med olika alternativ. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativ för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visningsalternativ för presentationsfiler. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visningsalternativ för projektledningsfiler. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Inaktiverar rendering av kommentarer när den är satt till `true`. Som standard är den `false` — alla kommentarer visas. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiverar rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar och annotationer för vissa format |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Ställer in säkerhetsalternativen för utdata‑PDF‑dokumentet. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativ för kalkylbladsfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Visningsalternativ för textfiler. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visningsalternativ för Visio-filer. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textvattenstämpeln som ska tillämpas på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Visningsalternativ för webbfil. |
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
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
