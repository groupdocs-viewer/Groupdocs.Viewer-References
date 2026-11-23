---
title: "ViewInfoOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni utilizzate per recuperare informazioni sulla visualizzazione."
type: docs
weight: 34
url: /it/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Fornisce opzioni utilizzate per recuperare informazioni sulla visualizzazione.


La classe ViewInfoOptions incapsula impostazioni e parametri aggiuntivi che
possono essere usati per recuperare informazioni su una vista nel componente GroupDocs.Viewer.


Esempio di utilizzo:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Indica se l'estrazione del testo è abilitata. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Imposta il flag che indica se l'estrazione del testo è abilitata. |
|
|  | [getMaxWidth()](#getMaxWidth--) | Restituisce la larghezza massima dell'immagine di output per il rendering in PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Imposta la larghezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [getMaxHeight()](#getMaxHeight--) | Restituisce l'altezza massima dell'immagine di output per il rendering in PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Imposta l'altezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [getWidth()](#getWidth--) | La larghezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [setWidth(int width)](#setWidth-int-) | La larghezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [getHeight()](#getHeight--) | L'altezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [setHeight(int height)](#setHeight-int-) | L'altezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG). |
|
|  | [forHtmlView()](#forHtmlView--) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in HTML.
|
|  | [forJpgView()](#forJpgView--) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in JPG.
|
|  | [forPngView()](#forPngView--) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in PNG.
|
|  | [forPdfView()](#forPdfView--) | Inizializza una nuova istanza della classe ViewInfoOptions per recuperare informazioni sulla vista durante il rendering in PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe basata sull'oggetto [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe basata sull'oggetto [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Inizializza una nuova istanza di |
ViewInfoOptions
classe basata sull'oggetto [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Inizializza una nuova istanza della classe [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basata su un oggetto PdfViewOptions. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indica se l'estrazione del testo è abilitata.
Utilizza questa proprietà per ottenere il testo contenuto in un documento sorgente e le sue coordinate. Quindi puoi usare questi dati per aggiungere un testo selezionabile sull'immagine o per implementare una ricerca di testo nel rendering basato su immagine. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - True se l'estrazione del testo è abilitata, false altrimenti.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Imposta il flag che indica se l'estrazione del testo è abilitata.
Utilizza questa proprietà per ottenere il testo contenuto in un documento sorgente e le sue coordinate. Quindi puoi usare questi dati per aggiungere un testo selezionabile sull'immagine o per implementare una ricerca di testo nel rendering basato su immagine. Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | extractText | boolean | True per abilitare l'estrazione del testo, false per disabilitarla. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Restituisce la larghezza massima dell'immagine di output per il rendering in PNG/JPG.
Utilizza questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Se imposti la proprietà, questa proprietà viene ignorata.


**Returns:**
int - la larghezza massima dell'immagine di output.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Imposta la larghezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Se imposti la proprietà, questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxWidth | int | La larghezza massima dell'immagine di output. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Restituisce l'altezza massima dell'immagine di output per il rendering in PNG/JPG.
Utilizza questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Se imposti la proprietà, questa proprietà viene ignorata.


**Returns:**
int - l'altezza massima dell'immagine di output.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Imposta l'altezza massima di un'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Se imposti la proprietà, questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxHeight | int | L'altezza massima dell'immagine di output. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


La larghezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Se imposti questa proprietà, la proprietà viene ignorata.


**Returns:**
int - la larghezza dell'immagine.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


La larghezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Se imposti questa proprietà, la proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | width | int | La larghezza dell'immagine. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


L'altezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Se imposti questa proprietà, la proprietà viene ignorata.


**Returns:**
int - l'altezza dell'immagine.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


L'altezza dell'immagine di output (in pixel, solo per il rendering in PNG/JPG).
Utilizza questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Se imposti questa proprietà, la proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | altezza | int | L'altezza dell'immagine. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderSinglePage | boolean | Consente al contenuto HTML di essere renderizzato su una singola pagina. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in JPG.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | extractText | boolean | Consente l'estrazione del testo. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe per recuperare informazioni sulla vista durante il rendering in PNG.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | extractText | boolean | Consente l'estrazione del testo. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Inizializza una nuova istanza della classe ViewInfoOptions per recuperare informazioni sulla vista durante il rendering in PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe basata sull'oggetto [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Le opzioni di visualizzazione HTML. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe basata sull'oggetto [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Le opzioni di visualizzazione PNG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Inizializza una nuova istanza di
ViewInfoOptions
classe basata sull'oggetto [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Le opzioni di visualizzazione JPG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Inizializza una nuova istanza della classe [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basata su un oggetto PdfViewOptions.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Le opzioni di visualizzazione PDF. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

