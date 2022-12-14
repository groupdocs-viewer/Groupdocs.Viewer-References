---
title: SpreadsheetOptions
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Bietet Optionen zum Rendern von Tabellenkalkulationen.
type: docs
weight: 520
url: /de/net/groupdocs.viewer.options/spreadsheetoptions/
---
## SpreadsheetOptions class

Bietet Optionen zum Rendern von Tabellenkalkulationen.

```csharp
public class SpreadsheetOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Trennzeichen erkennen (für CSV/TSV-Dateien). |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Aktiviert das Rendern von Rasterlinien. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Aktiviert das Rendern von Überschriften. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Aktiviert das Rendern ausgeblendeter Spalten. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Aktiviert das Rendern ausgeblendeter Zeilen. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Deaktiviert das Rendern leerer Spalten. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Deaktiviert das Rendern leerer Zeilen. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Der Textüberlaufmodus zum Rendern von Tabellendokumenten in HTML. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Initialisiert eine neue Instanz von[`SpreadsheetOptions`](../spreadsheetoptions) Klasse zum Rendern des gesamten Blatts in eine Seite. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Initialisiert eine neue Instanz von[`SpreadsheetOptions`](../spreadsheetoptions) nur zum Rendern von Druckbereichen. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Initialisiert eine neue Instanz von[`SpreadsheetOptions`](../spreadsheetoptions) nur zum Rendern von Druckbereichen. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Initialisiert eine neue Instanz von[`SpreadsheetOptions`](../spreadsheetoptions) zum Rendern von Blättern in Seiten. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Initialisiert eine neue Instanz von[`SpreadsheetOptions`](../spreadsheetoptions) zum Rendern von Blättern in Seiten. |

### Siehe auch

* namensraum [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
