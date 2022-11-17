---
title: PngViewOptions
second_title: GroupDocs.Viewer för .NET API-referens
description: Ger alternativ för att rendera dokument till PNGformat.
type: docs
weight: 440
url: /sv/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Ger alternativ för att rendera dokument till PNG-format.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initierar ny instans av[`PngViewOptions`](../pngviewoptions) class. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initierar ny instans av[`PngViewOptions`](../pngviewoptions) class. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initierar ny instans av[`PngViewOptions`](../pngviewoptions) class. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initierar ny instans av[`PngViewOptions`](../pngviewoptions) class. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initierar ny instans av[`PngViewOptions`](../pngviewoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativen för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Alternativen för CAD-ritningsvy. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardteckensnitt som ska användas när ett visst teckensnitt som används i dokumentet inte kan hittas. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visa alternativen för e-postmeddelanden. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Aktiverar textextraktion. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Höjden på en utdatabild i pixlar. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visa alternativ för e-postlagringsdatafiler. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Max höjd för en utdatabild i pixlar. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Max bredd på en utdatabild i pixlar. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativen för MS Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativen för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visa alternativ för presentationsbearbetning av dokument. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visa alternativ för projekthanteringsfiler. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Möjliggör rendering av kommentarer. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Möjliggör rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativen för kalkylarksfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Textfiler som delar upp till sidoralternativ. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio-filer som behandlar dokumentvyalternativ. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Textens vattenstämpel som appliceras på varje sida. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De här renderingsalternativen gör att du kan anpassa utseendet på HTML/PDF/PNG/JPEG-utdata när du renderar webbdokument. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | Bredden på utdatabilden i pixlar. |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
