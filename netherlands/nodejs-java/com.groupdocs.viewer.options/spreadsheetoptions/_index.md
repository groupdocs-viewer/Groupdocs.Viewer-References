---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van spreadsheets."
type: docs
weight: 31
url: /nl/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Biedt opties voor het renderen van spreadsheets.

De SpreadsheetOptions‑klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om de weergave van spreadsheet‑bestanden (zoals Excel‑ of CSV‑bestanden) in de GroupDocs.Viewer‑component te regelen. Voor details, zie de subonderwerpen van het [Render spreadsheet files][]‑onderwerp.

Voorbeeldgebruik:

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

| Methode | Beschrijving |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Bepaalt of het werkblad moet worden weergegeven per pagina‑breuk. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Stelt in of het werkblad moet worden gerenderd op pagina-einden. |
| [isDetectSeparator()](#isDetectSeparator--) | Detecteert het scheidingsteken voor CSV/TSV-bestanden. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Stelt in of het scheidingsteken voor CSV/TSV-bestanden moet worden gedetecteerd. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Maakt een nieuw exemplaar van de klasse SpreadsheetOptions aan voor het renderen van één blad op één pagina. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Maakt een nieuw exemplaar van de klasse SpreadsheetOptions aan voor het renderen van een blad op meerdere pagina's. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initialiseert een nieuw exemplaar van de klasse SpreadsheetOptions voor het renderen van een blad op pagina's. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initialiseert een nieuw exemplaar van de klasse SpreadsheetOptions voor het alleen renderen van afdrukgebieden. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Geeft aan of één blad wordt gerenderd op één pagina. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Haalt het aantal rijen op dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Haalt het aantal kolommen op dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Stelt het aantal kolommen in dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Geeft aan of alleen de afdrukgebieden worden gerenderd. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Wanneer deze optie is ingeschakeld, wordt een werkblad gerenderd op paginabreaks die binnen het afdrukgebied vallen. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Stelt in of een werkblad moet worden gerenderd op paginabreaks die binnen het afdrukgebied vallen. |
| [isRenderGridLines()](#isRenderGridLines--) | Schakelt het renderen van rasterlijnen in. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Schakelt het renderen van rasterlijnen in of uit. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Geeft aan of lege rijen moeten worden overgeslagen tijdens het renderen. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Stelt in of lege rijen moeten worden overgeslagen tijdens het renderen. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Geeft aan of lege kolommen moeten worden overgeslagen tijdens het renderen. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Stelt in of lege kolommen moeten worden overgeslagen tijdens het renderen. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Bepaalt of verborgen rijen moeten worden gerenderd. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Stelt in of verborgen rijen moeten worden gerenderd. |
| [isRenderHeadings()](#isRenderHeadings--) | Controleert of het renderen van kopteksten is ingeschakeld. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Schakelt het renderen van kopteksten in. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Schakelt het renderen van verborgen kolommen in. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Schakelt het renderen van verborgen kolommen in. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Retourneert de tekst‑overloopmodus voor het renderen van spreadsheet‑documenten naar HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Stelt de tekst‑overloopmodus in voor het renderen van spreadsheet‑documenten naar HTML. |
| [getLeftMargin()](#getLeftMargin--) | Om de linkermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Om de linkermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. |
| [getRightMargin()](#getRightMargin--) | Om de rechtermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Om de rechtermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [getTopMargin()](#getTopMargin--) | Om de bovenmarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Om de bovenmarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [getBottomMargin()](#getBottomMargin--) | Om de ondermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Om de ondermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initialiseert een nieuw exemplaar van SpreadsheetOptions voor het renderen van afdrukgebieden en pagina‑onderbrekingen. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initialiseert een nieuw exemplaar van de klasse SpreadsheetOptions voor het alleen renderen van afdrukgebieden. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Bepaalt of het werkblad moet worden weergegeven per pagina‑breuk.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  als het werkblad per pagina‑onderbrekingen moet worden gerenderd,  false  anders.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Stelt in of het werkblad moet worden gerenderd op pagina-einden.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  als het werkblad per pagina‑onderbrekingen moet worden gerenderd,  false  anders. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detecteert het scheidingsteken voor CSV/TSV-bestanden.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  als het scheidingsteken automatisch moet worden gedetecteerd,  false  anders.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Stelt in of het scheidingsteken voor CSV/TSV-bestanden moet worden gedetecteerd.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| detectSeparator | boolean | true  om het scheidingsteken automatisch te detecteren,  false  anders. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Maakt een nieuw exemplaar van de klasse SpreadsheetOptions aan voor het renderen van één blad op één pagina.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Maakt een nieuw exemplaar van de klasse SpreadsheetOptions aan voor het renderen van een blad op meerdere pagina's.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| countRowsPerPage | int | Het aantal rijen dat in elke pagina moet worden opgenomen. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initialiseert een nieuw exemplaar van de klasse SpreadsheetOptions voor het renderen van een blad op pagina's.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| countRowsPerPage | int | Het aantal rijen dat op elke pagina moet worden opgenomen. |
| countColumnsPerPage | int | Het aantal kolommen dat op elke pagina moet worden opgenomen. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initialiseert een nieuw exemplaar van de klasse SpreadsheetOptions voor het alleen renderen van afdrukgebieden.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Geeft aan of één blad wordt gerenderd op één pagina.

**Returns:**
boolean -  true  als één blad wordt gerenderd op één pagina;  false  anders.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Haalt het aantal rijen op dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - het aantal rijen dat in elke pagina moet worden opgenomen.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Haalt het aantal kolommen op dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - het aantal kolommen dat in elke pagina moet worden opgenomen.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Stelt het aantal kolommen in dat in elke pagina moet worden opgenomen bij het splitsen van het werkblad in pagina's.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| countColumnsPerPage | int | Het aantal kolommen dat in elke pagina moet worden opgenomen. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Geeft aan of alleen de afdrukgebieden worden gerenderd.

**Returns:**
boolean -  true  als alleen de afdrukgebieden worden gerenderd,  false  anders.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Wanneer deze optie is ingeschakeld, wordt een werkblad gerenderd op paginabreaks die binnen het afdrukgebied vallen.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Stelt in of een werkblad moet worden gerenderd op paginabreaks die binnen het afdrukgebied vallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Stel in op true om in te schakelen, false om uit te schakelen. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Schakelt het renderen van rasterlijnen in.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  als rasterlijnen zijn ingeschakeld,  false  anders.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Schakelt het renderen van rasterlijnen in of uit.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om rasterlijnen weer te geven,  false  om dit uit te schakelen. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Geeft aan of lege rijen moeten worden overgeslagen tijdens het renderen.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  als lege rijen moeten worden overgeslagen,  false  anders.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Stelt in of lege rijen moeten worden overgeslagen tijdens het renderen.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om lege rijen over te slaan,  false  anders. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Geeft aan of lege kolommen moeten worden overgeslagen tijdens het renderen.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  als lege kolommen worden overgeslagen,  false  anders.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Stelt in of lege kolommen moeten worden overgeslagen tijdens het renderen.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om lege kolommen over te slaan,  false  anders. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Bepaalt of verborgen rijen moeten worden gerenderd.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  als verborgen rijen moeten worden gerenderd,  false  anders.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Stelt in of verborgen rijen moeten worden gerenderd.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om het renderen van verborgen rijen in te schakelen,  false  om dit uit te schakelen. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Controleert of het renderen van kopteksten is ingeschakeld.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  als kopteksten weergeven is ingeschakeld,  false  anders.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Schakelt het renderen van kopteksten in.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderHeadings | boolean | true  om kopteksten weer te geven,  false  om uit te schakelen. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Schakelt het renderen van verborgen kolommen in.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  als verborgen kolommen weergeven is ingeschakeld,  false  anders.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Schakelt het renderen van verborgen kolommen in.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om verborgen kolommen weer te geven,  false  om uit te schakelen. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Retourneert de tekst‑overloopmodus voor het renderen van spreadsheet‑documenten naar HTML.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Stelt de tekst‑overloopmodus in voor het renderen van spreadsheet‑documenten naar HTML. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | De tekst‑overloopmodus die moet worden ingesteld. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Om de linkermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt.

Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Om de linkermarge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaardconversiewaarde gebruikt.

Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Om de rechter marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Om de rechter marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Om de bovenste marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Om de bovenste marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Om de onderste marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Om de onderste marge van het werkblad in te stellen bij het converteren naar pdf; als deze kleiner is dan 0, wordt de standaard conversiewaarde gebruikt. Als de parameter kleiner is dan 0, wordt de standaardwaarde gebruikt. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initialiseert een nieuw exemplaar van  SpreadsheetOptions  voor het renderen van afdrukgebieden en pagina‑breuken. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initialiseert een nieuw exemplaar van de  SpreadsheetOptions  klasse voor uitsluitend het renderen van afdrukgebieden. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
