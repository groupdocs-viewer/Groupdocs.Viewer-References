---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Optionen zum Rendern von Tabellenkalkulationen bereit."
type: docs
weight: 31
url: /de/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Stellt Optionen zum Rendern von Tabellenkalkulationen bereit.

Die Klasse SpreadsheetOptions fasst verschiedene Einstellungen und Parameter zusammen, die zur Steuerung der Darstellung von Tabellenkalkulationsdateien (wie Excel- oder CSV-Dateien) in der GroupDocs.Viewer-Komponente verwendet werden können. Weitere Details finden Sie in den Unterpunkten des Themas [Render spreadsheet files][].

Beispielhafte Verwendung:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Bestimmt, ob das Arbeitsblatt anhand von Seitenumbrüchen gerendert werden soll. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Legt fest, ob das Arbeitsblatt durch Seitenumbrüche gerendert werden soll. |
| [isDetectSeparator()](#isDetectSeparator--) | Ermittelt das Trennzeichen für CSV/TSV-Dateien. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Legt fest, ob das Trennzeichen für CSV/TSV-Dateien ermittelt werden soll. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Erstellt eine neue Instanz der Klasse  SpreadsheetOptions  zum Rendern eines Blatts auf einer Seite. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Erstellt eine neue Instanz der Klasse  SpreadsheetOptions  zum Rendern eines Blatts auf mehreren Seiten. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern eines Blatts auf Seiten. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern ausschließlich von Druckbereichen. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Gibt an, ob ein Blatt auf einer Seite gerendert wird. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Ermittelt die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Ermittelt die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Legt die Anzahl der Spalten fest, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Gibt an, ob nur die Druckbereiche gerendert werden. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Wenn diese Option aktiviert ist, wird ein Arbeitsblatt durch Seitenumbrüche gerendert, die innerhalb des Druckbereichs liegen. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Legt fest, ob ein Arbeitsblatt durch Seitenumbrüche gerendert werden soll, die innerhalb des Druckbereichs liegen. |
| [isRenderGridLines()](#isRenderGridLines--) | Aktiviert das Rendern von Gitternetzlinien. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Aktiviert oder deaktiviert das Rendern von Gitternetzlinien. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Gibt an, ob leere Zeilen beim Rendern übersprungen werden sollen. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Legt fest, ob leere Zeilen beim Rendern übersprungen werden sollen. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Gibt an, ob leere Spalten beim Rendern übersprungen werden sollen. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Legt fest, ob leere Spalten beim Rendern übersprungen werden sollen. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Bestimmt, ob versteckte Zeilen gerendert werden sollen. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Legt fest, ob versteckte Zeilen gerendert werden sollen. |
| [isRenderHeadings()](#isRenderHeadings--) | Prüft, ob das Rendern von Überschriften aktiviert ist. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Aktiviert das Rendern von Überschriften. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Aktiviert das Rendern versteckter Spalten. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Aktiviert das Rendern versteckter Spalten. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Gibt den Textüberlaufmodus für die Darstellung von Tabellenkalkulationsdokumenten in HTML zurück. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Legt den Textüberlaufmodus für die Darstellung von Tabellenkalkulationsdokumenten in HTML fest. |
| [getLeftMargin()](#getLeftMargin--) | Um den linken Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Um den linken Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. |
| [getRightMargin()](#getRightMargin--) | Um den rechten Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Um den rechten Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [getTopMargin()](#getTopMargin--) | Um den oberen Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Um den oberen Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [getBottomMargin()](#getBottomMargin--) | Um den unteren Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Um den unteren Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initialisiert eine neue Instanz von  SpreadsheetOptions  für die Darstellung von Druckbereichen und Seitenumbrüchen. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern ausschließlich von Druckbereichen. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Bestimmt, ob das Arbeitsblatt anhand von Seitenumbrüchen gerendert werden soll.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  wenn das Arbeitsblatt nach Seitenumbrüchen dargestellt werden soll,  false  sonst.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Legt fest, ob das Arbeitsblatt durch Seitenumbrüche gerendert werden soll.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  wenn das Arbeitsblatt nach Seitenumbrüchen dargestellt werden soll,  false  sonst. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Ermittelt das Trennzeichen für CSV/TSV-Dateien.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  wenn das Trennzeichen automatisch erkannt werden soll,  false  sonst.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Legt fest, ob das Trennzeichen für CSV/TSV-Dateien ermittelt werden soll.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| detectSeparator | boolean | true  um das Trennzeichen automatisch zu erkennen,  false  sonst. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Erstellt eine neue Instanz der Klasse  SpreadsheetOptions  zum Rendern eines Blatts auf einer Seite.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Erstellt eine neue Instanz der Klasse  SpreadsheetOptions  zum Rendern eines Blatts auf mehreren Seiten.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| countRowsPerPage | int | Die Anzahl der Zeilen, die in jeder Seite enthalten sein sollen. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern eines Blatts auf Seiten.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| countRowsPerPage | int | Die Anzahl der Zeilen, die auf jeder Seite enthalten sein sollen. |
| countColumnsPerPage | int | Die Anzahl der Spalten, die auf jeder Seite enthalten sein sollen. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern ausschließlich von Druckbereichen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Gibt an, ob ein Blatt auf einer Seite gerendert wird.

**Returns:**
boolean -  true  wenn ein Blatt in eine Seite gerendert wird;  false  sonst.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Ermittelt die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Ermittelt die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Legt die Anzahl der Spalten fest, die in jede Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| countColumnsPerPage | int | Die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Gibt an, ob nur die Druckbereiche gerendert werden.

**Returns:**
boolean -  true  wenn nur die Druckbereiche dargestellt werden,  false  sonst.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Wenn diese Option aktiviert ist, wird ein Arbeitsblatt durch Seitenumbrüche gerendert, die innerhalb des Druckbereichs liegen.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Legt fest, ob ein Arbeitsblatt durch Seitenumbrüche gerendert werden soll, die innerhalb des Druckbereichs liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Auf true setzen, um zu aktivieren, false um zu deaktivieren. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Aktiviert das Rendern von Gitternetzlinien.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  wenn Rasterlinien aktiviert sind,  false  sonst.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Aktiviert oder deaktiviert das Rendern von Gitternetzlinien.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Aktivieren der Rasterliniendarstellung,  false  zum Deaktivieren. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Gibt an, ob leere Zeilen beim Rendern übersprungen werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  wenn leere Zeilen übersprungen werden sollen,  false  sonst.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Legt fest, ob leere Zeilen beim Rendern übersprungen werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Überspringen leerer Zeilen,  false  sonst. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Gibt an, ob leere Spalten beim Rendern übersprungen werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  wenn leere Spalten übersprungen werden,  false  sonst.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Legt fest, ob leere Spalten beim Rendern übersprungen werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Überspringen leerer Spalten,  false  sonst. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Bestimmt, ob versteckte Zeilen gerendert werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  wenn ausgeblendete Zeilen dargestellt werden sollen,  false  sonst.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Legt fest, ob versteckte Zeilen gerendert werden sollen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Aktivieren der Darstellung ausgeblendeter Zeilen,  false  zum Deaktivieren. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Prüft, ob das Rendern von Überschriften aktiviert ist.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  wenn die Überschriftsdarstellung aktiviert ist,  false  sonst.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Aktiviert das Rendern von Überschriften.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderHeadings | boolean | true  zum Aktivieren der Überschriftsdarstellung,  false  zum Deaktivieren. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Aktiviert das Rendern versteckter Spalten.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  wenn die Darstellung ausgeblendeter Spalten aktiviert ist,  false  sonst.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Aktiviert das Rendern versteckter Spalten.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Aktivieren der Darstellung ausgeblendeter Spalten,  false  zum Deaktivieren. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Gibt den Textüberlaufmodus für die Darstellung von Tabellenkalkulationsdokumenten in HTML zurück.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Legt den Textüberlaufmodus für die Darstellung von Tabellendokumenten in HTML fest. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Der zu setzende Textüberlaufmodus. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Um den linken Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet.

Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Um den linken Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet.

Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Um den rechten Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Um den rechten Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Um den oberen Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Um den oberen Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Um den unteren Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Um den unteren Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird, wenn er kleiner als 0 ist, der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initialisiert eine neue Instanz von  SpreadsheetOptions  für die Darstellung von Druckbereichen und Seitenumbrüchen. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse für die Darstellung ausschließlich von Druckbereichen. Für Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
