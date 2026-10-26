---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Innehåller alternativ för att hämta information om vyn."
type: docs
weight: 580
url: /sv/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Innehåller alternativ för att hämta information om vyn.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Visningsalternativ för arkivfiler. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Visningsalternativ för CAD-ritningar. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Ställer in standardteckensnittet för ett dokument. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Visningsalternativ för e-postmeddelanden. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Aktiverar textutvinning. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Höjden på den utgående bilden (i pixlar, endast för rendering till PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Visningsalternativ för e-postlagringsdatafiler. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Ställer in den maximala höjden på en utgående bild (i pixlar, endast för rendering till PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Ställer in den maximala bredden på en utgående bild (i pixlar, endast för rendering till PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Visningsalternativ för Microsoft Outlook-datafiler. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Visningsalternativ för PDF-dokument. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Visningsalternativ för presentationsfiler. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Visningsalternativ för projektledningsfiler. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Inaktiverar rendering av kommentarer när den är satt till `true`. Som standard är den `false` — alla kommentarer visas. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Aktiverar rendering av dolda sidor. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Aktiverar rendering av anteckningar och annotationer för vissa format |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Visningsalternativ för kalkylbladsfiler. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Visningsalternativ för textfiler. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visningsalternativ för Visio-filer. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Visningsalternativ för webbfil. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Bredden på den utgående bilden (i pixlar, endast för rendering till PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Visningsalternativ för ordbehandlingsfiler. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) för att hämta information om vyn vid rendering till PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) baserat på objektet [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) baserat på objektet [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) baserat på objektet [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initierar en instans av klassen [`ViewInfoOptions`](../viewinfooptions) baserat på objektet [`PngViewOptions`](../pngviewoptions). |

### Se även

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
