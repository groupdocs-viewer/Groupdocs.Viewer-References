---
title: "ViewOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Contiene le opzioni di rendering."
type: docs
weight: 35
url: /it/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Contiene le opzioni di rendering.


La classe ViewOptions estende la classe BaseViewOptions e funge da classe base per le opzioni di rendering
nel componente GroupDocs.Viewer. Incapsula impostazioni e parametri comuni che possono essere utilizzati
per il rendering di vari tipi di documenti in diversi formati.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Ottiene la filigrana di testo applicata a ogni pagina. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Imposta la filigrana di testo da applicare a ogni pagina. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Applica una rotazione in senso orario alla pagina specificata. |
|
|  | [getPageRotations()](#getPageRotations--) | Recupera le rotazioni delle pagine. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Per evitare di creare l'istanza solo per verificare che sia vuota |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Ottiene la filigrana di testo applicata a ogni pagina.


Nel caso in cui entrambi #setWatermark(Watermark).setWatermark(Watermark) e #getPageRotations().getPageRotations() siano specificati,
la filigrana verrà applicata alle pagine ruotate.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Imposta la filigrana di testo da applicare a ogni pagina.


Nel caso in cui entrambi
ViewOptions.Watermark
e #getPageRotations().getPageRotations() siano specificati,
la filigrana verrà applicata alle pagine ruotate.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | La filigrana di testo da impostare. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Applica una rotazione in senso orario alla pagina specificata.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumber | int | Il numero di pagina deve essere strettamente maggiore di 0. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Il valore di rotazione. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Recupera le rotazioni delle pagine.


Se entrambi [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) e
getPageRotations()
sono specificati,
la filigrana verrà applicata alle pagine ruotate.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - una mappa contenente i numeri di pagina come chiavi e le loro rotazioni corrispondenti come valori.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Per evitare di creare l'istanza solo per verificare che sia vuota


**Returns:**
boolean
