---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Tabellenkalkulationen bereit."
type: docs
weight: 31
url: /de/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Stellt Optionen zum Rendern von Tabellenkalkulationen bereit.


Die Klasse SpreadsheetOptions kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um die Darstellung von Tabellenkalkulationsdateien (wie Excel- oder CSV-Dateien) in der GroupDocs.Viewer-Komponente zu steuern.
Weitere Details finden Sie unter den Unterpunkten des Themas [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/).


Beispielverwendung:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Bestimmt, ob das Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Legt fest, ob das Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | Ermittelt das Trennzeichen für CSV/TSV-Dateien. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Legt fest, ob das Trennzeichen für CSV/TSV-Dateien ermittelt werden soll. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | Erstellt eine neue Instanz von |
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf einer Seite.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Erstellt eine neue Instanz von |
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf mehreren Seiten.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initialisiert eine neue Instanz von |
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf Seiten.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | Initialisiert eine neue Instanz von |
SpreadsheetOptions
Klasse zur reinen Darstellung von Druckbereichen.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | Gibt an, ob ein Blatt auf einer Seite dargestellt wird. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | Ermittelt die Anzahl der Zeilen, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Ermittelt die Anzahl der Spalten, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Legt die Anzahl der Spalten fest, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Gibt an, ob nur die Druckbereiche dargestellt werden. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Wenn diese Option aktiviert ist, wird ein Arbeitsblatt anhand von Seitenumbrüchen dargestellt, die innerhalb des Druckbereichs liegen. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Legt fest, ob ein Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll, die innerhalb des Druckbereichs liegen. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | Aktiviert die Darstellung von Gitternetzlinien. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Aktiviert oder deaktiviert die Darstellung von Gitternetzlinien. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | Gibt an, ob leere Zeilen bei der Darstellung übersprungen werden sollen. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Legt fest, ob leere Zeilen beim Rendern übersprungen werden sollen. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Gibt an, ob leere Spalten beim Rendern übersprungen werden sollen. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Legt fest, ob leere Spalten beim Rendern übersprungen werden sollen. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | Bestimmt, ob versteckte Zeilen gerendert werden sollen. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Legt fest, ob versteckte Zeilen gerendert werden sollen. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | Überprüft, ob die Überschriftsdarstellung aktiviert ist. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Aktiviert die Überschriftsdarstellung. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Aktiviert die Darstellung versteckter Spalten. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Aktiviert die Darstellung versteckter Spalten. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | Gibt den Textüberlaufmodus für das Rendern von Tabellendokumenten in HTML zurück. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Legt den Textüberlaufmodus für das Rendern von Tabellendokumenten in HTML fest. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Um den linken Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Um den linken Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. |
|
|  | [getRightMargin()](#getRightMargin--) | Um den rechten Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | Um den rechten Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [getTopMargin()](#getTopMargin--) | Um den oberen Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | Um den oberen Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Um den unteren Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Um den unteren Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Liest oder legt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Legt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Liest oder legt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Legt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initialisiert eine neue Instanz von  SpreadsheetOptions  für das Rendern von Druckbereichen und Seitenumbrüchen. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initialisiert eine neue Instanz der Klasse  SpreadsheetOptions  ausschließlich für das Rendern von Druckbereichen. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Bestimmt, ob das Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  wenn das Arbeitsblatt nach Seitenumbrüchen gerendert werden soll,  false  sonst.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Legt fest, ob das Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | renderByPageBreaks | boolesch | true  wenn das Arbeitsblatt nach Seitenumbrüchen gerendert werden soll,  false  sonst. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Ermittelt das Trennzeichen für CSV/TSV-Dateien.


Für weitere Details siehe die [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Returns:**
boolean -  true  wenn das Trennzeichen automatisch erkannt werden soll,  false  sonst.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Legt fest, ob das Trennzeichen für CSV/TSV-Dateien ermittelt werden soll.


Für weitere Details siehe die [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | detectSeparator | boolesch | true  um den Trennzeichen automatisch zu erkennen,  false  andernfalls. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Erstellt eine neue Instanz von
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf einer Seite.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Erstellt eine neue Instanz von
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf mehreren Seiten.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | countRowsPerPage | int | Die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initialisiert eine neue Instanz von
SpreadsheetOptions
Klasse zur Darstellung eines Blatts auf Seiten.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | countRowsPerPage | int | Die Anzahl der Zeilen, die auf jeder Seite aufgenommen werden sollen. |
|
|  | countColumnsPerPage | int | Die Anzahl der Spalten, die auf jeder Seite aufgenommen werden sollen. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initialisiert eine neue Instanz von
SpreadsheetOptions
Klasse zur reinen Darstellung von Druckbereichen.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Gibt an, ob ein Blatt auf einer Seite dargestellt wird.


**Returns:**
boolean -  true  wenn ein Blatt auf eine Seite gerendert wird;  false  andernfalls.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Ermittelt die Anzahl der Zeilen, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
int - die Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Ermittelt die Anzahl der Spalten, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
int - die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Legt die Anzahl der Spalten fest, die pro Seite aufgenommen werden sollen, wenn das Arbeitsblatt in Seiten aufgeteilt wird.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | countColumnsPerPage | int | Die Anzahl der Spalten, die in jede Seite aufgenommen werden sollen. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Gibt an, ob nur die Druckbereiche dargestellt werden.


**Returns:**
boolean -  true  wenn nur die Druckbereiche gerendert werden,  false  andernfalls.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Wenn diese Option aktiviert ist, wird ein Arbeitsblatt anhand von Seitenumbrüchen dargestellt, die innerhalb des Druckbereichs liegen.


**Returns:**
boolesch
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Legt fest, ob ein Arbeitsblatt anhand von Seitenumbrüchen dargestellt werden soll, die innerhalb des Druckbereichs liegen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolesch | Auf true setzen, um zu aktivieren, false zum Deaktivieren. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Aktiviert die Darstellung von Gitternetzlinien.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  wenn Rasterlinien aktiviert sind,  false  andernfalls.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Aktiviert oder deaktiviert die Darstellung von Gitternetzlinien.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um das Rendern von Rasterlinien zu aktivieren,  false  um es zu deaktivieren. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Gibt an, ob leere Zeilen bei der Darstellung übersprungen werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  wenn leere Zeilen übersprungen werden sollen,  false  andernfalls.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Legt fest, ob leere Zeilen beim Rendern übersprungen werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um leere Zeilen zu überspringen,  false  andernfalls. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Gibt an, ob leere Spalten beim Rendern übersprungen werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  wenn leere Spalten übersprungen werden,  false  andernfalls.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Legt fest, ob leere Spalten beim Rendern übersprungen werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um leere Spalten zu überspringen,  false  sonst. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Bestimmt, ob versteckte Zeilen gerendert werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  wenn versteckte Zeilen gerendert werden sollen,  false  sonst.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Legt fest, ob versteckte Zeilen gerendert werden sollen.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um das Rendern versteckter Zeilen zu aktivieren,  false  um es zu deaktivieren. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Überprüft, ob die Überschriftsdarstellung aktiviert ist.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
boolean -  true  wenn das Rendern von Überschriften aktiviert ist,  false  sonst.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Aktiviert die Überschriftsdarstellung.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | renderHeadings | boolesch | true  um das Rendern von Überschriften zu aktivieren,  false  um es zu deaktivieren. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Aktiviert die Darstellung versteckter Spalten.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  wenn das Rendern versteckter Spalten aktiviert ist,  false  sonst.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Aktiviert die Darstellung versteckter Spalten.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um das Rendern versteckter Spalten zu aktivieren,  false  um es zu deaktivieren. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Gibt den Textüberlaufmodus für das Rendern von Tabellendokumenten in HTML zurück.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Legt den Textüberlaufmodus für das Rendern von Tabellendokumenten in HTML fest. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Der zu setzende Textüberlaufmodus. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Um den linken Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet.


Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Um den linken Rand des Arbeitsblatts beim Konvertieren zu PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet.


Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Um den rechten Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Um den rechten Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Um den oberen Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Um den oberen Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Um den unteren Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Um den unteren Rand des Arbeitsblatts beim Konvertieren in PDF festzulegen, wird bei einem Wert kleiner als 0 der Standardkonvertierungswert verwendet. Wenn der Parameter kleiner als 0 ist, wird der Standardwert verwendet. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Liest oder setzt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellen in PNG- oder JPEG-Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Returns:**
int - die horizontale Auflösung in DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Legt die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | horizontalResolution | int | die horizontale Auflösung in DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Liest oder legt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Returns:**
int - die vertikale Auflösung in DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Legt die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll fest. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet.


Standardwert ist 96 DPI. Minimal möglicher Wert – 72 DPI, maximal möglicher Wert – 600 DPI.
Wenn der vom Benutzer angegebene Wert außerhalb dieser Grenzen liegt, wird der minimale bzw. maximale mögliche Wert verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | verticalResolution | int | die vertikale Auflösung in DPI. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initialisiert eine neue Instanz von  SpreadsheetOptions  zum Rendern von Druckbereichen und Seitenumbrüchen. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initialisiert eine neue Instanz der  SpreadsheetOptions  Klasse zum Rendern von Druckbereichen ausschließlich. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

