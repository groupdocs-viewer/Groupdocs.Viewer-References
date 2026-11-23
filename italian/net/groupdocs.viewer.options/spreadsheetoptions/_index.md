---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Contiene opzioni per il rendering dei fogli di calcolo. Per i dettagli, vedere i figli della sezione Render spreadsheet files https//docs.groupdocs.com/viewer/net/renderspreadsheets/ topic."
type: docs
weight: 530
url: /it/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Contiene opzioni per il rendering dei fogli di calcolo. Per ulteriori dettagli, vedere le sezioni figlie dell'argomento [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Imposta il margine inferiore di una pagina durante la conversione in PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Il numero di colonne da includere in ogni pagina durante la suddivisione del foglio di lavoro in pagine. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Il numero di righe da includere in ogni pagina durante la suddivisione del foglio di lavoro in pagine. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Rileva un separatore (per file CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Imposta il margine sinistro di una pagina durante la conversione in PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Consente il rendering delle linee della griglia. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Consente il rendering delle intestazioni. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Consente il rendering delle colonne nascoste. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Consente il rendering delle righe nascoste. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Imposta il margine destro di una pagina durante la conversione in PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Disabilita il rendering delle colonne vuote. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Disabilita il rendering delle righe vuote. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Imposta la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML. Per impostazione predefinita è , che imita il comportamento predefinito di MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Imposta il margine superiore di una pagina durante la conversione in PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per il rendering dell'intero foglio in una sola pagina. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per suddividere in pagine tramite interruzioni di pagina. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per il rendering solo delle aree di stampa. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per il rendering delle aree di stampa e delle interruzioni di pagina. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per il rendering del foglio in pagine. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Inizializza un'istanza della classe [`SpreadsheetOptions`](../spreadsheetoptions) per il rendering del foglio in pagine. |

### Vedi anche

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
