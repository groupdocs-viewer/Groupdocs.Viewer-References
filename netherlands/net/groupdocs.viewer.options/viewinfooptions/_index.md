---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Bevat opties voor het ophalen van informatie over de weergave."
type: docs
weight: 580
url: /nl/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Bevat opties voor het ophalen van informatie over de weergave.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergave‑opties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergave‑opties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Stelt het standaardlettertype voor een document in. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergave‑opties voor e‑mailberichten. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Schakelt tekstextractie in. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | De hoogte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | De weergave‑opties voor e‑mailopslag‑databestanden. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Stelt de maximale hoogte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Stelt de maximale breedte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | De weergave‑opties voor Microsoft Outlook‑databestanden. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | De weergave‑opties voor PDF‑documenten. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | De weergave‑opties voor presentaties. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | De weergave‑opties voor projectmanagement‑bestanden. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Schakelt het renderen van opmerkingen uit wanneer ingesteld op `true`. Standaard is `false` — alle opmerkingen worden weergegeven. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Schakelt het renderen van verborgen pagina's in. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Schakelt het renderen van notities en annotaties in voor sommige indelingen. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | De weergave‑opties voor spreadsheet‑bestanden. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | De weergave‑opties voor tekstbestanden. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | De weergave‑opties voor Visio‑bestanden. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De weergave‑opties voor webbestanden. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | De breedte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | De weergave‑opties voor tekstverwerkingsbestanden. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse om informatie over de weergave op te halen bij het renderen naar PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse op basis van het [`HtmlViewOptions`](../htmlviewoptions) object. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse op basis van het [`JpgViewOptions`](../jpgviewoptions) object. |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse op basis van het [`PdfViewOptions`](../pdfviewoptions) object. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initialiseert een instantie van de [`ViewInfoOptions`](../viewinfooptions) klasse op basis van het [`PngViewOptions`](../pngviewoptions) object. |

### Zie ook

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
