---
title: "SpreadsheetOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei fogli di calcolo."
type: docs
weight: 31
url: /it/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Fornisce opzioni per il rendering dei fogli di calcolo.


La classe SpreadsheetOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per controllare il rendering dei file di foglio di calcolo (come file Excel o CSV) nel componente GroupDocs.Viewer.
Per ulteriori dettagli, vedere le sotto-sezioni dell'argomento [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/).


Esempio di utilizzo:

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


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Determina se il foglio di lavoro deve essere renderizzato mediante interruzioni di pagina. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Imposta se il foglio di lavoro deve essere renderizzato mediante interruzioni di pagina. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | Rileva il separatore per i file CSV/TSV. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Imposta se rilevare il separatore per i file CSV/TSV. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | Crea una nuova istanza di |
SpreadsheetOptions
classe per il rendering di un foglio in una pagina.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Crea una nuova istanza di |
SpreadsheetOptions
classe per il rendering di un foglio in più pagine.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Inizializza una nuova istanza di |
SpreadsheetOptions
classe per il rendering di un foglio in pagine.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | Inizializza una nuova istanza di |
SpreadsheetOptions
classe per il rendering solo delle aree di stampa.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | Indica se un foglio è renderizzato in una pagina. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | Ottiene il numero di righe da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Ottiene il numero di colonne da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Imposta il numero di colonne da includere in ogni pagina durante la divisione del foglio di lavoro in pagine. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indica se vengono renderizzate solo le aree di stampa. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Quando questa opzione è abilitata, un foglio di lavoro verrà renderizzato in base alle interruzioni di pagina che rientrano nell'area di stampa. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Imposta se renderizzare un foglio di lavoro in base alle interruzioni di pagina che rientrano nell'area di stampa. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | Abilita il rendering delle linee della griglia. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Abilita o disabilita il rendering delle linee della griglia. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | Indica se le righe vuote devono essere saltate durante il rendering. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Imposta se le righe vuote devono essere saltate durante il rendering. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Indica se le colonne vuote devono essere saltate durante il rendering. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Imposta se le colonne vuote devono essere saltate durante il rendering. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | Determina se le righe nascoste devono essere renderizzate. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Imposta se le righe nascoste devono essere renderizzate. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | Verifica se il rendering delle intestazioni è abilitato. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Abilita il rendering delle intestazioni. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Abilita il rendering delle colonne nascoste. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Abilita il rendering delle colonne nascoste. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | Restituisce la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Imposta la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Imposta il margine sinistro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Imposta il margine sinistro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. |
|
|  | [getRightMargin()](#getRightMargin--) | Imposta il margine destro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | Imposta il margine destro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [getTopMargin()](#getTopMargin--) | Imposta il margine superiore del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | Imposta il margine superiore del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Imposta il margine inferiore del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Imposta il margine inferiore del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene o imposta la risoluzione orizzontale per le immagini generate in punti per pollice. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Imposta la risoluzione orizzontale per le immagini generate in punti per pollice. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Ottiene o imposta la risoluzione verticale per le immagini generate in punti per pollice. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Imposta la risoluzione verticale per le immagini generate in punti per pollice. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Inizializza una nuova istanza di SpreadsheetOptions per il rendering delle aree di stampa e delle interruzioni di pagina. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Inizializza una nuova istanza della classe SpreadsheetOptions per il rendering solo delle aree di stampa. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Determina se il foglio di lavoro deve essere renderizzato mediante interruzioni di pagina.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  se il foglio di lavoro deve essere renderizzato per interruzioni di pagina,  false  altrimenti.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Imposta se il foglio di lavoro deve essere renderizzato mediante interruzioni di pagina.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  se il foglio di lavoro deve essere renderizzato per interruzioni di pagina,  false  altrimenti. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Rileva il separatore per i file CSV/TSV.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Returns:**
boolean -  true  se il separatore deve essere rilevato automaticamente,  false  altrimenti.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Imposta se rilevare il separatore per i file CSV/TSV.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | detectSeparator | boolean | true  per rilevare automaticamente il separatore,  false  altrimenti. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Crea una nuova istanza di
SpreadsheetOptions
classe per il rendering di un foglio in una pagina.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Crea una nuova istanza di
SpreadsheetOptions
classe per il rendering di un foglio in più pagine.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | countRowsPerPage | int | Il numero di righe da includere in ogni pagina. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Inizializza una nuova istanza di
SpreadsheetOptions
classe per il rendering di un foglio in pagine.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | countRowsPerPage | int | Il numero di righe da includere in ogni pagina. |
|
|  | countColumnsPerPage | int | Il numero di colonne da includere in ogni pagina. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Inizializza una nuova istanza di
SpreadsheetOptions
classe per il rendering solo delle aree di stampa.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indica se un foglio è renderizzato in una pagina.


**Returns:**
boolean -  true  se un foglio è renderizzato in una pagina;  false  altrimenti.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Ottiene il numero di righe da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
int - il conteggio delle righe da includere in ogni pagina.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Ottiene il numero di colonne da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
int - il conteggio delle colonne da includere in ogni pagina.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Imposta il numero di colonne da includere in ogni pagina durante la divisione del foglio di lavoro in pagine.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | countColumnsPerPage | int | Il conteggio delle colonne da includere in ogni pagina. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indica se vengono renderizzate solo le aree di stampa.


**Returns:**
boolean -  true  se vengono renderizzate solo le aree di stampa,  false  altrimenti.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Quando questa opzione è abilitata, un foglio di lavoro verrà renderizzato in base alle interruzioni di pagina che rientrano nell'area di stampa.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Imposta se renderizzare un foglio di lavoro in base alle interruzioni di pagina che rientrano nell'area di stampa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | Imposta su true per abilitare, false per disabilitare. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Abilita il rendering delle linee della griglia.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  se le linee della griglia sono abilitate,  false  altrimenti.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Abilita o disabilita il rendering delle linee della griglia.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il rendering delle linee della griglia,  false  per disabilitarlo. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Indica se le righe vuote devono essere saltate durante il rendering.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  se le righe vuote devono essere saltate,  false  altrimenti.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Imposta se le righe vuote devono essere saltate durante il rendering.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per saltare le righe vuote,  false  altrimenti. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Indica se le colonne vuote devono essere saltate durante il rendering.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  se le colonne vuote sono saltate,  false  altrimenti.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Imposta se le colonne vuote devono essere saltate durante il rendering.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per saltare le colonne vuote,  false  altrimenti. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Determina se le righe nascoste devono essere renderizzate.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  se le righe nascoste devono essere renderizzate,  false  altrimenti.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Imposta se le righe nascoste devono essere renderizzate.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il rendering delle righe nascoste,  false  per disabilitarlo. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Verifica se il rendering delle intestazioni è abilitato.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
boolean -  true  se il rendering delle intestazioni è abilitato,  false  altrimenti.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Abilita il rendering delle intestazioni.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderHeadings | boolean | true  per abilitare il rendering delle intestazioni,  false  per disabilitarlo. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Abilita il rendering delle colonne nascoste.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  se il rendering delle colonne nascoste è abilitato,  false  altrimenti.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Abilita il rendering delle colonne nascoste.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il rendering delle colonne nascoste,  false  per disabilitarlo. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Restituisce la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Imposta la modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | La modalità di overflow del testo da impostare. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Imposta il margine sinistro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito.


Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Imposta il margine sinistro del foglio di lavoro durante la conversione in PDF; se inferiore a 0, viene utilizzato il valore di conversione predefinito.


Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Per impostare il margine destro del foglio di lavoro durante la conversione in PDF, se inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Per impostare il margine destro del foglio di lavoro durante la conversione in PDF, se inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Per impostare il margine superiore del foglio di lavoro durante la conversione in PDF, se inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Per impostare il margine superiore del foglio di lavoro durante la conversione in PDF, se inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Per impostare il margine inferiore del foglio di lavoro durante la conversione in PDF, se è inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Per impostare il margine inferiore del foglio di lavoro durante la conversione in PDF, se è inferiore a 0 viene utilizzato il valore di conversione predefinito. Se il parametro è inferiore a 0, viene utilizzato il valore predefinito. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Ottiene o imposta la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Returns:**
int - la risoluzione orizzontale in DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Imposta la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | horizontalResolution | int | la risoluzione orizzontale in DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Ottiene o imposta la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Returns:**
int - la risoluzione verticale in DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Imposta la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | verticalResolution | int | la risoluzione verticale in DPI. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Inizializza una nuova istanza di  SpreadsheetOptions  per il rendering delle aree di stampa e delle interruzioni di pagina. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Inizializza una nuova istanza della classe  SpreadsheetOptions  per il rendering delle sole aree di stampa. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

