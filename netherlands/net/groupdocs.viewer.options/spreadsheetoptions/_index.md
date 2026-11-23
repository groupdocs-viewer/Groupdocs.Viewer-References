---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Bevat opties voor het renderen van spreadsheets. Voor details zie de subonderdelen van de Render‑spreadsheet‑bestanden https//docs.groupdocs.com/viewer/net/renderspreadsheets/ onderwerp."
type: docs
weight: 530
url: /nl/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Bevat opties voor het renderen van spreadsheets. Voor details, zie de onderliggende items van het [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/)‑onderwerp.

```csharp
public class SpreadsheetOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Stelt de ondermarge van een pagina in bij het converteren naar PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Het aantal kolommen dat op elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Het aantal rijen dat op elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Detecteer een scheidingsteken (voor CSV/TSV‑bestanden). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Haalt op of stelt de horizontale resolutie voor gegenereerde afbeeldingen in dots per inch in. Deze optie wordt alleen gebruikt bij het renderen van spreadsheets naar PNG‑ of JPEG‑formaten. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Stelt de linkermarge van een pagina in bij het converteren naar PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Schakelt het renderen van rasterlijnen in. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Schakelt het renderen van koppen in. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Schakelt het renderen van verborgen kolommen in. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Schakelt het renderen van verborgen rijen in. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Stelt de rechtermarge van een pagina in bij het converteren naar PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Schakelt het renderen van lege kolommen uit. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Schakelt het renderen van lege rijen uit. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Stelt de tekst‑overloopmodus in voor het renderen van spreadsheet‑documenten naar HTML. Standaard is , wat het standaardgedrag van MS Excel nabootst. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Stelt de bovenmarge van een pagina in bij het converteren naar PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Haalt de verticale resolutie op of stelt deze in voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van spreadsheets naar PNG‑ of JPEG‑formaten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor het renderen van het volledige blad op één pagina. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor het splitsen in pagina's op basis van pagina‑eindes. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor uitsluitend het renderen van de afdrukgebieden. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor het renderen van afdrukgebieden en pagina‑eindes. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor het renderen van het blad in pagina's. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Initialiseert een instantie van de [`SpreadsheetOptions`](../spreadsheetoptions)‑klasse voor het renderen van het blad in pagina's. |

### Zie ook

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
