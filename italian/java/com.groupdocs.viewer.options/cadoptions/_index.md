---
title: "CadOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering di disegni CAD."
type: docs
weight: 13
url: /it/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Fornisce opzioni per il rendering di disegni CAD.


La classe CadOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per controllare il rendering dei disegni CAD nel componente GroupDocs.Viewer.


Per ulteriori informazioni e esempi di codice, vedere i [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) e i [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


Esempio di utilizzo:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | Recupera il file PC3 (Plotter Configuration) associato al plotter. |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Imposta il file PC3 (Plotter Configuration) associato al plotter. |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Inizializza una nuova istanza di |
CadOptions
classe per il rendering per fattore di scala.
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Inizializza una nuova istanza di |
CadOptions
classe per il rendering per larghezza.
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Inizializza una nuova istanza di |
CadOptions
classe per il rendering per altezza.
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Inizializza una nuova istanza di |
CadOptions
classe per il rendering per larghezza e altezza.
|
|  | [getScaleFactor()](#getScaleFactor--) | Ottiene il fattore di scala per il rendering. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza del risultato di output in pixel. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza del risultato di output in pixel. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Restituisce il colore di sfondo dell'immagine. |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Restituisce il colore di sfondo dell'immagine. |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Imposta il colore di sfondo dell'immagine. |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Imposta il colore di sfondo dell'immagine. |
|
|  | [getTiles()](#getTiles--) | Restituisce le regioni di disegno da renderizzare. |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Imposta le regioni di disegno da renderizzare. |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | Indica se i layout del documento CAD devono essere renderizzati. |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Imposta se i layout del documento CAD devono essere renderizzati. |
|
|  | [getLayoutName()](#getLayoutName--) | Restituisce il nome del layout specifico da renderizzare. |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Imposta il nome del layout specifico da renderizzare. |
|
|  | [getLayers()](#getLayers--) | Restituisce i livelli di disegno CAD da renderizzare. |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Restituisce i livelli di disegno CAD da renderizzare. |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Impostare questo flag su true abilita una modalità di conversione speciale orientata alle prestazioni per tutti i formati della famiglia CAD. |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Impostare questo flag su true abilita una modalità di conversione speciale orientata alle prestazioni per tutti i formati della famiglia CAD. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Verifica se questo oggetto CadOptions è uguale a un altro oggetto. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Recupera il file PC3 (Plotter Configuration) associato al plotter.


**Returns:**
java.lang.String - il percorso del file PC3.

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Imposta il file PC3 (Plotter Configuration) associato al plotter.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pc3File | java.lang.String | Il percorso del file PC3. |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Inizializza una nuova istanza di
CadOptions
classe per il rendering per fattore di scala.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | scaleFactor | double | Il fattore di scala per il rendering. Valori maggiori di 1 ingrandiranno il risultato di output, mentre valori compresi tra 0 e 1 lo ridurranno. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Inizializza una nuova istanza di
CadOptions
classe per il rendering per larghezza.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | width | int | La larghezza del risultato di output in pixel. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Inizializza una nuova istanza di
CadOptions
classe per il rendering per altezza.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | altezza | int | L'altezza del risultato di output in pixel. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Inizializza una nuova istanza di
CadOptions
classe per il rendering per larghezza e altezza.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | width | int | La larghezza del risultato di output in pixel. |
|
|  | altezza | int | L'altezza del risultato di output in pixel. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Ottiene il fattore di scala per il rendering.
Valori superiori a 1 ingrandiranno il risultato di output, mentre valori compresi tra 0 e 1 lo ridurranno.


**Returns:**
double - il fattore di scala per il rendering.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza del risultato di output in pixel.


**Returns:**
int - la larghezza del risultato di output.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza del risultato di output in pixel.


**Returns:**
int - l'altezza del risultato di output.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Restituisce il colore di sfondo dell'immagine.


**Returns:**
java.awt.Color - il colore di sfondo dell'immagine.

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Restituisce il colore di sfondo dell'immagine.


**Returns:**
java.lang.String - il colore di sfondo dell'immagine in formato 0xFFFFFF.

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Imposta il colore di sfondo dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | Il colore di sfondo dell'immagine. |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Imposta il colore di sfondo dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | colorName | java.lang.String | Il nome del colore di sfondo dell'immagine. |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Restituisce le regioni di disegno da renderizzare.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Il
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
e
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) le opzioni sono ignorate
quando si esegue il rendering a tasselli.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - l'elenco delle regioni di disegno da renderizzare.

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Imposta le regioni di disegno da renderizzare.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Il
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
e
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) le opzioni sono ignorate
quando si esegue il rendering a tasselli.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<com.groupdocs.viewer.options.Tile> | L'elenco delle regioni di disegno da renderizzare. |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Indica se i layout del documento CAD devono essere renderizzati.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Per impostazione predefinita, solo il Modello viene renderizzato.*


**Returns:**
boolean -  true  se i layout devono essere renderizzati,  false  altrimenti.

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Imposta se i layout del documento CAD devono essere renderizzati.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Per impostazione predefinita, solo il Modello viene renderizzato.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per renderizzare i layout,  false  altrimenti. |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Ottiene il nome del layout specifico da renderizzare. Il nome del layout è sensibile al maiuscolo/minuscolo.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Per impostazione predefinita, solo il Modello viene renderizzato.*


**Returns:**
java.lang.String - il nome del layout specifico da renderizzare.

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Imposta il nome del layout specifico da renderizzare. Il nome del layout è sensibile al maiuscolo/minuscolo.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Per impostazione predefinita, solo il Modello viene renderizzato.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome del layout specifico da renderizzare. |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Restituisce i livelli di disegno CAD da renderizzare.


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - i layer di disegno CAD.

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Restituisce i livelli di disegno CAD da renderizzare.
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.List<com.groupdocs.viewer.results.Layer> | I livelli di disegno CAD. |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Impostare questo flag su true abilita una modalità di conversione speciale orientata alle prestazioni per tutti i formati della famiglia CAD. In questa modalità, la velocità di conversione è molto più rapida, ma la qualità dei documenti risultanti è significativamente peggiore. Per impostazione predefinita, è disabilitata (false). La qualità dei documenti risultanti è la migliore possibile a scapito delle prestazioni.


**Returns:**
boolean -  true  se la modalità di conversione orientata alle prestazioni è abilitata,  false  altrimenti.

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Impostare questo flag su true abilita una modalità di conversione speciale orientata alle prestazioni per tutti i formati della famiglia CAD. In questa modalità, la velocità di conversione è molto più rapida, ma la qualità dei documenti risultanti è significativamente peggiore. Per impostazione predefinita, è disabilitata (false). La qualità dei documenti risultanti è la migliore possibile a scapito delle prestazioni.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  per abilitare la modalità di conversione orientata alle prestazioni,  false  per disabilitarla. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se questo oggetto CadOptions è uguale a un altro oggetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | o | java.lang.Object | L'oggetto con cui confrontare. |
|

**Returns:**
boolean -  true  se gli oggetti sono uguali,  false  altrimenti.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcola il valore del codice hash per questo oggetto. Il codice hash è basato su
lo stato interno dell'oggetto ed è usato nelle strutture dati basate su hash
come mappe hash e set hash.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - il valore del codice hash per questo oggetto.

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa di questo oggetto.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - una rappresentazione stringa di questo oggetto.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Restituisce una rappresentazione stringa di questo oggetto.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stile | org.apache.commons.lang3.builder.ToStringStyle | Il ToStringStyle da utilizzare per generare la rappresentazione stringa. |
|

**Returns:**
java.lang.String - una rappresentazione stringa di questo oggetto usando il ToStringStyle specificato.

