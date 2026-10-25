---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av kalkylblad."
type: docs
weight: 31
url: /sv/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Tillhandahåller alternativ för rendering av kalkylblad.


Klassen SpreadsheetOptions kapslar in olika inställningar och parametrar som kan användas
för att kontrollera rendering av kalkylbladsfiler (såsom Excel- eller CSV-filer) i GroupDocs.Viewer-komponenten.
För detaljer, se underavsnittet av ämnet [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/).


Exempel på användning:

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


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Bestämmer om kalkylbladet ska renderas efter sidbrytningar. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Ställer in om kalkylbladet ska renderas efter sidbrytningar. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | Detekterar avgränsaren för CSV/TSV-filer. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Ställer in om avgränsaren för CSV/TSV-filer ska detekteras. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | Skapar en ny instans av |
SpreadsheetOptions
klass för att rendera ett blad till en sida.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Skapar en ny instans av |
SpreadsheetOptions
klass för att rendera ett blad till flera sidor.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initierar en ny instans av |
SpreadsheetOptions
klass för att rendera ett blad till sidor.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | Initierar en ny instans av |
SpreadsheetOptions
klass för att endast rendera utskriftsområden.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | Indikerar om ett blad renderas till en sida. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | Hämtar antalet rader som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Hämtar antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Ställer in antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Anger om endast utskriftsområdena ska renderas. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | När detta alternativ är aktiverat kommer ett kalkylblad att renderas efter sidbrytningar som ligger inom utskriftsområdet. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Ställer in om ett kalkylblad ska renderas efter sidbrytningar som ligger inom utskriftsområdet. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | Aktiverar rendering av rutnätslinjer. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Aktiverar eller inaktiverar rendering av rutnätslinjer. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | Anger om tomma rader ska hoppas över vid rendering. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Ställer in om tomma rader ska hoppas över vid rendering. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Anger om tomma kolumner ska hoppas över vid rendering. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Ställer in om tomma kolumner ska hoppas över vid rendering. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | Bestämmer om dolda rader ska renderas. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Ställer in om dolda rader ska renderas. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | Kontrollerar om rubrikrendering är aktiverad. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Aktiverar rubrikrendering. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Aktiverar rendering av dolda kolumner. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Aktiverar rendering av dolda kolumner. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | Returnerar textöversvämningsläget för rendering av kalkylbladdokument till HTML. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Ställer in textöversvämningsläget för rendering av kalkylbladdokument till HTML. |
|
|  | [getLeftMargin()](#getLeftMargin--) | För att ange vänstermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | För att ange vänstermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. |
|
|  | [getRightMargin()](#getRightMargin--) | För att ange högermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | För att ange högermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [getTopMargin()](#getTopMargin--) | För att ange topmargin för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | För att ange topmargin för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [getBottomMargin()](#getBottomMargin--) | För att ange bottenmarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | För att ange bottenmarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar eller anger den horisontella upplösningen för genererade bilder i punkter per tum. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Ställer in den horisontella upplösningen för genererade bilder i punkter per tum. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Hämtar eller anger den vertikala upplösningen för genererade bilder i punkter per tum. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Ställer in den vertikala upplösningen för genererade bilder i punkter per tum. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initierar en ny instans av  SpreadsheetOptions  för att rendera utskriftsområden och sidbrytningar. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initierar en ny instans av klassen  SpreadsheetOptions  för att endast rendera utskriftsområden. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Bestämmer om kalkylbladet ska renderas efter sidbrytningar.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  om kalkylbladet ska renderas efter sidbrytningar,  false  annars.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Ställer in om kalkylbladet ska renderas efter sidbrytningar.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  om kalkylbladet ska renderas efter sidbrytningar,  false  annars. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detekterar avgränsaren för CSV/TSV-filer.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Returns:**
boolean -  true  om separatorn ska upptäckas automatiskt,  false  annars.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Ställer in om avgränsaren för CSV/TSV-filer ska detekteras.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | detectSeparator | boolean | true  för att automatiskt upptäcka separatorn,  false  annars. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Skapar en ny instans av
SpreadsheetOptions
klass för att rendera ett blad till en sida.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Skapar en ny instans av
SpreadsheetOptions
klass för att rendera ett blad till flera sidor.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | countRowsPerPage | int | Antalet rader som ska inkluderas på varje sida. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initierar en ny instans av
SpreadsheetOptions
klass för att rendera ett blad till sidor.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | countRowsPerPage | int | Antalet rader som ska inkluderas på varje sida. |
|
|  | countColumnsPerPage | int | Antalet kolumner som ska inkluderas på varje sida. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initierar en ny instans av
SpreadsheetOptions
klass för att endast rendera utskriftsområden.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indikerar om ett blad renderas till en sida.


**Returns:**
boolean -  true  om ett blad renderas på en sida;  false  annars.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Hämtar antalet rader som ska inkluderas på varje sida när kalkylbladet delas upp i sidor.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
int - antalet rader som ska inkluderas i varje sida.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Hämtar antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
int - antalet kolumner som ska inkluderas i varje sida.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Ställer in antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | countColumnsPerPage | int | Antalet kolumner som ska inkluderas i varje sida. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Anger om endast utskriftsområdena ska renderas.


**Returns:**
boolean -  true  om endast utskriftsområden renderas,  false  annars.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


När detta alternativ är aktiverat kommer ett kalkylblad att renderas efter sidbrytningar som ligger inom utskriftsområdet.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Ställer in om ett kalkylblad ska renderas efter sidbrytningar som ligger inom utskriftsområdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | Ställ in på true för att aktivera, false för att inaktivera. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Aktiverar rendering av rutnätslinjer.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  om rutnätslinjer är aktiverade,  false  annars.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Aktiverar eller inaktiverar rendering av rutnätslinjer.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera rendering av rutnätslinjer,  false  för att inaktivera den. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Anger om tomma rader ska hoppas över vid rendering.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  om tomma rader ska hoppas över,  false  annars.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Ställer in om tomma rader ska hoppas över vid rendering.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att hoppa över tomma rader,  false  annars. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Anger om tomma kolumner ska hoppas över vid rendering.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  om tomma kolumner hoppas över,  false  annars.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Ställer in om tomma kolumner ska hoppas över vid rendering.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att hoppa över tomma kolumner,  false  annars. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Bestämmer om dolda rader ska renderas.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  om dolda rader ska renderas,  false  annars.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Ställer in om dolda rader ska renderas.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att möjliggöra rendering av dolda rader,  false  för att inaktivera den. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Kontrollerar om rubrikrendering är aktiverad.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
boolean -  true  om rubrikrendering är aktiverad,  false  annars.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Aktiverar rubrikrendering.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderHeadings | boolean | true  för att aktivera rubrikrendering,  false  för att inaktivera. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Aktiverar rendering av dolda kolumner.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  om rendering av dolda kolumner är aktiverad,  false  annars.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Aktiverar rendering av dolda kolumner.


För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera rendering av dolda kolumner,  false  för att inaktivera. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Returnerar textöversvämningsläget för rendering av kalkylbladdokument till HTML.
För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Ställer in textöversvämningsläget för rendering av kalkylbladsdokument till HTML. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Textöversvämningsläget som ska ställas in. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


För att ange vänstermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet.


Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


För att ange vänstermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet.


Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


För att ange högermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


För att ange högermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


För att ange övermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


För att ange övermarginalen för kalkylbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För mer information, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


För att ange bottenmarginalen för kalkylbladet vid konvertering till pdf, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


För att ange bottenmarginalen för kalkylbladet vid konvertering till pdf, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Hämtar eller anger den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Returns:**
int – den horisontella upplösningen i DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Anger den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | horizontalResolution | int | den horisontella upplösningen i DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Hämtar eller anger den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Returns:**
int – den vertikala upplösningen i DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Anger den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | verticalResolution | int | den vertikala upplösningen i DPI. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initierar en ny instans av  SpreadsheetOptions  för rendering av utskriftsområden och sidbrytningar. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initierar en ny instans av  SpreadsheetOptions  -klassen för rendering av utskriftsområden endast. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

