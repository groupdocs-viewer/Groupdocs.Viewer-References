---
title: ViewInfoOptions
second_title: GroupDocs.Viewer för .NET API-referens
description: Ger alternativ som används för att hämta information om vy.
type: docs
weight: 570
url: /sv/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Ger alternativ som används för att hämta information om vy.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativen för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Alternativen för CAD-ritningsvy. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Standardteckensnitt som ska användas när ett visst teckensnitt som används i dokumentet inte kan hittas. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visa alternativen för e-postmeddelanden. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Indikerar att textextraktion är aktiverad. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Bildhöjd (endast för rendering till PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visa alternativ för e-postlagringsdatafiler. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Maxhöjd på utdatabilden (endast för rendering till PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Max bredd på utdatabilden (endast för rendering till PNG/JPG) |
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
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De här renderingsalternativen gör att du kan anpassa utseendet på HTML/PDF/PNG/JPEG-utdata när du renderar webbdokument. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Bildbredd (endast för rendering till PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Med de här renderingsalternativen kan du anpassa utseendet på utdata HTML/PDF/PNG/JPEG när du renderar Word-dokument. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass för att hämta information om vy vid rendering till HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass för att hämta information om vy vid rendering till HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass för att hämta information om visning vid rendering till JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass för att hämta information om visning vid rendering till JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions)klass för att hämta information om vy vid rendering till PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions)klass för att hämta information om vy vid rendering till PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass baserat på[`HtmlViewOptions`](../htmlviewoptions) objekt. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass baserat på[`JpgViewOptions`](../jpgviewoptions) objekt. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initierar ny instans av[`ViewInfoOptions`](../viewinfooptions) klass baserat på[`PngViewOptions`](../pngviewoptions) objekt. |

### Se även

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namnutrymme [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
