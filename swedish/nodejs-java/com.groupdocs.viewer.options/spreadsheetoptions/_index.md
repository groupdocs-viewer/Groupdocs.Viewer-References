---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av kalkylblad."
type: docs
weight: 31
url: /sv/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Tillhandahåller alternativ för rendering av kalkylblad.

Klassen SpreadsheetOptions kapslar in olika inställningar och parametrar som kan användas för att kontrollera rendering av kalkylbladsfiler (såsom Excel- eller CSV-filer) i GroupDocs.Viewer-komponenten. För detaljer, se underavsnittet av ämnet [Render spreadsheet files][].

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Bestämmer om kalkylbladet ska renderas efter sidbrytningar. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Anger om kalkylbladet ska renderas efter sidbrytningar. |
| [isDetectSeparator()](#isDetectSeparator--) | Detekterar separatorn för CSV/TSV-filer. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Anger om separatorn för CSV/TSV-filer ska detekteras. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Skapar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till en sida. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Skapar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till flera sidor. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initierar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till sidor. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initierar en ny instans av klassen  SpreadsheetOptions  för att endast rendera utskriftsområden. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Indikerar om ett blad renderas till en sida. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Hämtar antalet rader som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Hämtar antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Anger antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indikerar om endast utskriftsområdena renderas. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | När detta alternativ är aktiverat kommer ett kalkylblad att renderas efter sidbrytningar som faller inom utskriftsområdet. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Anger om ett kalkylblad ska renderas efter sidbrytningar som faller inom utskriftsområdet. |
| [isRenderGridLines()](#isRenderGridLines--) | Aktiverar rendering av rutnätlinjer. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Aktiverar eller inaktiverar rendering av rutnätlinjer. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Indikerar om tomma rader ska hoppas över under rendering. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Anger om tomma rader ska hoppas över under rendering. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Indikerar om tomma kolumner ska hoppas över under rendering. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Anger om tomma kolumner ska hoppas över under rendering. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Bestämmer om dolda rader ska renderas. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Anger om dolda rader ska renderas. |
| [isRenderHeadings()](#isRenderHeadings--) | Kontrollerar om rendering av rubriker är aktiverad. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Aktiverar rendering av rubriker. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Aktiverar rendering av dolda kolumner. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Aktiverar rendering av dolda kolumner. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Returnerar läget för textöversvämning vid rendering av kalkylbladdokument till HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Ställer in läget för textöversvämning vid rendering av kalkylbladdokument till HTML. |
| [getLeftMargin()](#getLeftMargin--) | För att ange vänstermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | För att ange vänstermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. |
| [getRightMargin()](#getRightMargin--) | För att ange högermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | För att ange högermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [getTopMargin()](#getTopMargin--) | För att ange övermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | För att ange övermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [getBottomMargin()](#getBottomMargin--) | För att ange undre marginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | För att ange undre marginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initierar en ny instans av  SpreadsheetOptions  för rendering av utskriftsområden och sidbrytningar. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initierar en ny instans av klassen  SpreadsheetOptions  för att endast rendera utskriftsområden. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Bestämmer om kalkylbladet ska renderas efter sidbrytningar.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  om arbetsbladet ska renderas efter sidbrytningar,  false  annars.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Anger om kalkylbladet ska renderas efter sidbrytningar.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  om arbetsbladet ska renderas efter sidbrytningar,  false  annars. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detekterar separatorn för CSV/TSV-filer.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  om separatorn ska upptäckas automatiskt,  false  annars.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Anger om separatorn för CSV/TSV-filer ska detekteras.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| detectSeparator | boolean | true  för att automatiskt upptäcka separatorn,  false  annars. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Skapar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till en sida.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Skapar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till flera sidor.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| countRowsPerPage | int | Antalet rader som ska inkluderas på varje sida. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initierar en ny instans av klassen  SpreadsheetOptions  för att rendera ett blad till sidor.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| countRowsPerPage | int | Antalet rader som ska inkluderas på varje sida. |
| countColumnsPerPage | int | Antalet kolumner som ska inkluderas på varje sida. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initierar en ny instans av klassen  SpreadsheetOptions  för att endast rendera utskriftsområden.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

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

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - antalet rader som ska inkluderas på varje sida.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Hämtar antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - antalet kolumner som ska inkluderas på varje sida.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Anger antalet kolumner som ska inkluderas på varje sida när kalkylbladet delas upp i sidor.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| countColumnsPerPage | int | Antalet kolumner som ska inkluderas på varje sida. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indikerar om endast utskriftsområdena renderas.

**Returns:**
boolean -  true  om endast utskriftsområden renderas,  false  annars.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


När detta alternativ är aktiverat kommer ett kalkylblad att renderas efter sidbrytningar som faller inom utskriftsområdet.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Anger om ett kalkylblad ska renderas efter sidbrytningar som faller inom utskriftsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Ställ in på true för att aktivera, false för att inaktivera. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Aktiverar rendering av rutnätlinjer.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  om rutnätslinjer är aktiverade,  false  annars.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Aktiverar eller inaktiverar rendering av rutnätlinjer.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera rendering av rutnätslinjer,  false  för att inaktivera den. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Indikerar om tomma rader ska hoppas över under rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  om tomma rader ska hoppas över,  false  annars.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Anger om tomma rader ska hoppas över under rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att hoppa över tomma rader,  false  annars. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Indikerar om tomma kolumner ska hoppas över under rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  om tomma kolumner ska hoppas över,  false  annars.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Anger om tomma kolumner ska hoppas över under rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att hoppa över tomma kolumner,  false  annars. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Bestämmer om dolda rader ska renderas.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  om dolda rader ska renderas,  false  annars.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Anger om dolda rader ska renderas.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera rendering av dolda rader,  false  för att inaktivera den. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Kontrollerar om rendering av rubriker är aktiverad.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  om rubrikrendering är aktiverad,  false  annars.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Aktiverar rendering av rubriker.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderHeadings | boolean | true  för att aktivera rubrikrendering,  false  för att inaktivera. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Aktiverar rendering av dolda kolumner.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  om rendering av dolda kolumner är aktiverad,  false  annars.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Aktiverar rendering av dolda kolumner.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera rendering av dolda kolumner,  false  för att inaktivera. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Returnerar läget för textöversvämning vid rendering av kalkylbladdokument till HTML.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Ställer in textöversvämningsläget för rendering av kalkylbladsdokument till HTML. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Textöversvämningsläget som ska ställas in. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


För att ange vänstermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet.

Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


För att ange vänstermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet.

Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


För att ange högermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


För att ange högermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


För att ange övermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


För att ange övermarginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


För att ange undre marginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


För att ange undre marginalen för arbetsbladet vid konvertering till PDF, om den är mindre än 0 används standardkonverteringsvärdet. Om parametern är mindre än 0 används standardvärdet. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initierar en ny instans av  SpreadsheetOptions  för rendering av utskriftsområden och sidbrytningar. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initierar en ny instans av klassen  SpreadsheetOptions  för endast rendering av utskriftsområden. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
