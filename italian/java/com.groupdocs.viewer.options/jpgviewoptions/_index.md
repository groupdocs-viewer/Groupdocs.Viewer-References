---
title: "JpgViewOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei documenti in formato JPG."
type: docs
weight: 17
url: /it/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Fornisce opzioni per il rendering dei documenti in formato JPG.


La classe JpgViewOptions incapsula impostazioni e parametri aggiuntivi che possono essere utilizzati per controllare il rendering dei documenti
in formato JPG nel componente GroupDocs.Viewer.


Esempio di utilizzo:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inizializza una nuova istanza di |
JpgViewOptions
classe.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inizializza una nuova istanza di |
JpgViewOptions
classe.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inizializza una nuova istanza di |
JpgViewOptions
classe.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Inizializza una nuova istanza di |
JpgViewOptions
con "p_{0}.jpg" come formato del percorso file per i file di output.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Inizializza una nuova istanza di |
JpgViewOptions
classe.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Inizializza una nuova istanza di |
JpgViewOptions
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Restituisce la larghezza massima di un'immagine di output in pixel. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Imposta la larghezza massima di un'immagine di output in pixel. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Ottiene l'altezza massima di un'immagine di output in pixel. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Imposta l'altezza massima di un'immagine di output in pixel. |
|
|  | [getQuality()](#getQuality--) | Restituisce la qualità dell'immagine di output. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Imposta la qualità dell'immagine di output. |
|
|  | [isExtractText()](#isExtractText--) | Consente l'estrazione del testo. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Abilita o disabilita l'estrazione del testo. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza dell'immagine di output in pixel. |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza dell'immagine di output in pixel. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine di output in pixel. |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza dell'immagine di output in pixel. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Restituisce la factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Restituisce il callback per stimare l'avanzamento del salvataggio di un documento Words o Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Imposta il callback per stimare l'avanzamento del salvataggio di un documento Words o Email. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Inizializza una nuova istanza di
JpgViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inizializza una nuova istanza di
JpgViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Il metodo che rilascia lo stream creato dal metodo assegnato al delegato passato al parametro  createPageStream . |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Inizializza una nuova istanza di
JpgViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Inizializza una nuova istanza di
JpgViewOptions
con "p_{0}.jpg" come formato del percorso file per i file di output.
I file di output saranno collocati nella directory di lavoro corrente dell'applicazione.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Inizializza una nuova istanza di
JpgViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Il formato del percorso file, ad es., 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Inizializza una nuova istanza di
JpgViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Il formato del percorso file, ad es., 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Restituisce la larghezza massima di un'immagine di output in pixel.


Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Se imposti la proprietà #setWidth(int).setWidth(int), questa proprietà viene ignorata.


**Returns:**
int - la larghezza massima di un'immagine di output.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Imposta la larghezza massima di un'immagine di output in pixel.


Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Se imposti la proprietà #setWidth(int).setWidth(int), questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxWidth | int | La larghezza massima di un'immagine di output. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Ottiene l'altezza massima di un'immagine di output in pixel.


Usa questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Se imposti la proprietà #setHeight(int).setHeight(int), questa proprietà viene ignorata.


**Returns:**
int - l'altezza massima di un'immagine di output.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Imposta l'altezza massima di un'immagine di output in pixel.


Usa questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Se imposti la proprietà #setHeight(int).setHeight(int), questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxHeight | int | L'altezza massima di un'immagine di output. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Restituisce la qualità dell'immagine di output.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte - la qualità dell'immagine di output.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Imposta la qualità dell'immagine di output.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | La qualità dell'immagine di output. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Consente l'estrazione del testo.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  se l'estrazione del testo è abilitata,  false  altrimenti.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Abilita o disabilita l'estrazione del testo.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare l'estrazione del testo,  false  per disabilitarla. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza dell'immagine di output in pixel.


Usa questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Se imposti questa proprietà, la proprietà #setMaxWidth(int).setMaxWidth(int) viene ignorata.


**Returns:**
int - la larghezza dell'immagine di output.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza dell'immagine di output in pixel.


Usa questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Se imposti questa proprietà, la proprietà #setMaxWidth(int).setMaxWidth(int) viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza dell'immagine di output. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza dell'immagine di output in pixel.


Usa questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Se imposti questa proprietà, la proprietà #setMaxHeight(int).setMaxHeight(int) viene ignorata.


**Returns:**
int - l'altezza dell'immagine di output.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza dell'immagine di output in pixel.


Usa questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per un esempio di codice, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Se imposti questa proprietà, la proprietà #setMaxHeight(int).setMaxHeight(int) viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza dell'immagine di output. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Restituisce la factory che implementa i metodi per creare e rilasciare lo stream della pagina di output.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Restituisce il callback per stimare l'avanzamento del salvataggio di un documento Words o Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - il callback per stimare l'avanzamento del salvataggio del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Imposta il callback per stimare l'avanzamento del salvataggio di un documento Words o Email.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Il callback per stimare l'avanzamento del salvataggio del documento. |
|

