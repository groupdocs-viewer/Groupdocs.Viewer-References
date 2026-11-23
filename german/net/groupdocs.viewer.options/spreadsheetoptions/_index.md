---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Enthält Optionen zum Rendern von Tabellenkalkulationen. Weitere Details siehe die Unterelemente des Themas Render spreadsheet files https://docs.groupdocs.com/viewer/net/renderspreadsheets/."
type: docs
weight: 530
url: /de/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Enthält Optionen zum Rendern von Tabellenkalkulationen. Für Details siehe die Unterpunkte des Themas [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Setzt den unteren Rand einer Seite beim Konvertieren in PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Die Spaltenanzahl, die auf jeder Seite beim Aufteilen des Arbeitsblatts in Seiten enthalten sein soll. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Die Zeilenanzahl, die auf jeder Seite beim Aufteilen des Arbeitsblatts in Seiten enthalten sein soll. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Erkennt ein Trennzeichen (für CSV/TSV-Dateien). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Liest oder setzt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Setzt den linken Rand einer Seite beim Konvertieren in PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Aktiviert das Rendern von Gitternetzlinien. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Aktiviert das Rendern von Überschriften. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Aktiviert das Rendern versteckter Spalten. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Aktiviert das Rendern versteckter Zeilen. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Setzt den rechten Rand einer Seite beim Konvertieren in PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Deaktiviert das Rendern leerer Spalten. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Deaktiviert das Rendern leerer Zeilen. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Setzt den Textüberlaufmodus für das Rendern von Tabellenkalkulationsdokumenten in HTML. Standard ist , was das Standardverhalten von MS Excel nachahmt. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Setzt den oberen Rand einer Seite beim Konvertieren in PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Liest oder setzt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions) Klasse zum Rendern des gesamten Blatts auf einer Seite. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions) Klasse zum Aufteilen in Seiten anhand von Seitenumbrüchen. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions) Klasse zum Rendern ausschließlich der Druckbereiche. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions)-Klasse zum Rendern von Druckbereichen und Seitenumbrüchen. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions)-Klasse zum Rendern des Blatts in Seiten. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Initialisiert eine Instanz der [`SpreadsheetOptions`](../spreadsheetoptions)-Klasse zum Rendern des Blatts in Seiten. |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
