---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Bevat opties voor het renderen van documenten naar PNG-formaat. Voor details zie deze pagina https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ en de subpagina's."
type: docs
weight: 440
url: /nl/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Bevat opties voor het renderen van documenten naar PNG-indeling. Voor details, zie deze [pagina](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) en de onderliggende items.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initialiseert een instantie van de [`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initialiseert een instantie van de [`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initialiseert een instantie van de [`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initialiseert een instantie van de [`PngViewOptions`](../pngviewoptions) klasse. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initialiseert een instantie van de [`PngViewOptions`](../pngviewoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | De weergave‑opties voor archiefbestanden. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | De weergave‑opties voor CAD-tekeningen. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Stelt het standaardlettertype voor een document in. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | De weergave‑opties voor e‑mailberichten. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Schakelt tekstextractie in. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Stelt de hoogte van een uitvoerafbeelding in (in pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | De weergave‑opties voor e‑mailopslag‑databestanden. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Stelt de maximale hoogte van een uitvoerafbeelding in (in pixels). |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Stelt de maximale breedte van een uitvoerafbeelding in (in pixels). |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Het tekstwatermerk dat op elke pagina wordt toegepast. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | De weergave‑opties voor webbestanden. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | De breedte van de uitvoerafbeelding (in pixels). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | De weergave‑opties voor tekstverwerkingsbestanden. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Past de klokwijzerrotatie toe op een pagina. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | De paginarotatie. |

### Zie ook

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
