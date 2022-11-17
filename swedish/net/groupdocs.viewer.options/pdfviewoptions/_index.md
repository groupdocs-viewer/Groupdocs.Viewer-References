---
title: PdfViewOptions
second_title: GroupDocs.Viewer för .NET API-referens
description: Ger alternativ för att rendera dokument till PDFformat.
type: docs
weight: 420
url: /sv/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Ger alternativ för att rendera dokument till PDF-format.

```csharp
public class PdfViewOptions : ViewOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initierar ny instans av[`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initierar ny instans av[`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initierar ny instans av[`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initierar ny instans av[`PdfViewOptions`](../pdfviewoptions) class. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initierar ny instans av[`PdfViewOptions`](../pdfviewoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativen för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Alternativen för CAD-ritningsvy. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardteckensnitt som ska användas när ett visst teckensnitt som används i dokumentet inte kan hittas. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visa alternativen för e-postmeddelanden. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Höjden på en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Maxhöjd för en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Max bredd på en utdatabild i pixlar. (När du konverterar en bild till endast HTML) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Bredden på utdatabilden i pixlar. (När du konverterar en bild till endast HTML) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | Kvaliteten på JPG-bilderna som ingår i PDF-dokumentet; Giltiga värden är mellan 1 och 100; Standardvärdet är 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visa alternativ för e-postlagringsdatafiler. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativen för MS Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativen för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visa alternativ för presentationsbearbetning av dokument. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visa alternativ för projekthanteringsfiler. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Möjliggör rendering av kommentarer. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Möjliggör rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Säkerhetsalternativen för PDF-dokumentets utdata. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativen för kalkylarksfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textfiler som delar upp till sidoralternativ. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio-filer som behandlar dokumentvyalternativ. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textens vattenstämpel som appliceras på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De här renderingsalternativen gör att du kan anpassa utseendet på HTML/PDF/PNG/JPEG-utdata när du renderar webbdokument. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Med de här renderingsalternativen kan du anpassa utseendet på utdata HTML/PDF/PNG/JPEG när du renderar Word-dokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Tillämpar medurs rotation på sidan. |

## Fält

| namn | Beskrivning |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Sidrotationerna. |

### Se även

* class [ViewOptions](../viewoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
