---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Innehåller alternativ för att rendera kalkylblad. För detaljer, se underordnade till Render spreadsheet‑filer https//docs.groupdocs.com/viewer/net/renderspreadsheets/ ämnet."
type: docs
weight: 530
url: /sv/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Innehåller alternativ för rendering av kalkylblad. För detaljer, se underavsnitten till ämnet [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Ställer in den nedre marginalen på en sida vid konvertering till PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Antalet kolumner att inkludera på varje sida när arbetsbladet delas upp i sidor. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Antalet rader att inkludera på varje sida när arbetsbladet delas upp i sidor. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Detektera en separator (för CSV/TSV‑filer). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Hämtar eller anger den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG‑ eller JPEG‑format. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Ställer in den vänstra marginalen på en sida vid konvertering till PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Aktiverar rendering av rutnät. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Aktiverar rendering av rubriker. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Aktiverar rendering av dolda kolumner. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Aktiverar rendering av dolda rader. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Ställer in den högra marginalen på en sida vid konvertering till PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Inaktiverar rendering av tomma kolumner. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Inaktiverar rendering av tomma rader. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Ställer in textöversvämningsläget för rendering av kalkylbladdokument till HTML. Standard är , vilket efterliknar standardbeteendet i MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Ställer in den övre marginalen på en sida vid konvertering till PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Hämtar eller anger den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG‑ eller JPEG‑format. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att rendera hela bladet på en sida. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att dela upp i sidor vid sidbrytningar. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att endast rendera utskriftsområden. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att rendera utskriftsområden och sidbrytningar. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att rendera bladet i sidor. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Initierar en instans av klassen [`SpreadsheetOptions`](../spreadsheetoptions) för att rendera bladet i sidor. |

### Se även

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
