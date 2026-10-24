---
title: "PdfViewOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei documenti in formato PDF."
type: docs
weight: 23
url: /it/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Fornisce opzioni per il rendering dei documenti in formato PDF.


La classe PdfViewOptions incapsula impostazioni e parametri aggiuntivi
che può essere usata per controllare il rendering dei documenti in formato PDF nel componente GroupDocs.Viewer.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


Esempio di utilizzo:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Inizializza una nuova istanza di |
PdfViewOptions
classe.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Inizializza una nuova istanza di |
PdfViewOptions
classe.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Inizializza una nuova istanza della classe PdfViewOptions. |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | Inizializza una nuova istanza della classe PdfViewOptions con le impostazioni predefinite. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Inizializza una nuova istanza di |
PdfViewOptions
classe.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Inizializza una nuova istanza di |
PdfViewOptions
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Riduci la dimensione del file PDF di output applicando tecniche di ottimizzazione con diverse opzioni. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Riduci la dimensione del file PDF di output applicando tecniche di ottimizzazione con diverse opzioni. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Restituisce la larghezza massima di un'immagine di output in pixel. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Imposta la larghezza massima di un'immagine di output in pixel. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Restituisce l'altezza massima di un'immagine di output in pixel. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Imposta l'altezza massima di un'immagine di output in pixel. |
|
|  | [getImageWidth()](#getImageWidth--) | Restituisce la larghezza dell'immagine di output in pixel. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Imposta la larghezza dell'immagine di output in pixel. |
|
|  | [getImageHeight()](#getImageHeight--) | Recupera l'altezza dell'immagine di output in pixel. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Imposta l'altezza dell'immagine di output in pixel. |
|
|  | [getSecurity()](#getSecurity--) | Recupera le opzioni di sicurezza per il documento PDF di output. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Imposta le opzioni di sicurezza per il documento PDF di output. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Recupera il callback usato per stimare l'avanzamento del salvataggio di un documento Words o Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Imposta il callback usato per stimare l'avanzamento del salvataggio di un documento Words o Email. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Inizializza una nuova istanza di
PdfViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Inizializza una nuova istanza di
PdfViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Il metodo usato per istanziare lo stream per scrivere i dati del file di output. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Il metodo usato per rilasciare lo stream creato dal metodo  createFileStream  . |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Inizializza una nuova istanza della classe PdfViewOptions.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | La factory che implementa i metodi per creare e rilasciare lo stream del file di output. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Inizializza una nuova istanza della classe PdfViewOptions con le impostazioni predefinite.


Questo costruttore crea un nuovo
PdfViewOptions
oggetto con "output.pdf" come formato del percorso file per il file di output.
Il file di output sarà posizionato nella directory di lavoro corrente dell'applicazione.
Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Inizializza una nuova istanza di
PdfViewOptions
classe.


Questo costruttore crea un nuovo
PdfViewOptions
oggetto con il specificato
outputFilePath
parametro
che rappresenta il percorso per il file PDF di output.
Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | Il percorso per il file PDF di output. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Inizializza una nuova istanza di
PdfViewOptions
classe.


Per l'esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | Il percorso per il file PDF di output. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Riduci la dimensione del file PDF di output applicando tecniche di ottimizzazione con diverse opzioni.


Questa opzione è supportata per tutti i formati di file di input che sono supportati per la conversione in PDF: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Per dettagli e esempi di codice, vedere questa [pagina](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) e i suoi figli.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Riduci la dimensione del file PDF di output applicando tecniche di ottimizzazione con diverse opzioni.


Questa opzione è supportata per tutti i formati di file di input che sono supportati per la conversione in PDF: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Per dettagli e esempi di codice, vedere questa [pagina](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) e i suoi figli.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Oggetto PdfOptimizationOptions o null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Recupera la larghezza massima di un'immagine di output in pixel. Questo parametro si applica solo quando si converte un'immagine singola in HTML.


Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà quando rende un'immagine singola in PDF. Per dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti la proprietà, questa proprietà viene ignorata.


**Returns:**
int - la larghezza massima dell'immagine di output in pixel.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Imposta la larghezza massima di un'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà quando rende un'immagine singola in PDF. Per dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti la proprietà, questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageMaxWidth | int | La larghezza massima dell'immagine di output in pixel. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Recupera l'altezza massima di un'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Utilizza questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà durante il rendering di un'unica immagine in PDF. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti la proprietà, questa proprietà viene ignorata.


**Returns:**
int - l'altezza massima dell'immagine di output in pixel.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Imposta l'altezza massima di un'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Utilizza questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà solo durante il rendering di un'unica immagine in HTML. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti la proprietà, questa proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageMaxHeight | int | L'altezza massima dell'immagine di output in pixel. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Recupera la larghezza dell'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Utilizza questa proprietà per impostare la larghezza dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà durante il rendering di un'unica immagine in PDF. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti questa proprietà, la proprietà viene ignorata.


**Returns:**
int - la larghezza dell'immagine di output in pixel.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Imposta la larghezza dell'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un PDF contenente un'unica immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageWidth | int | La larghezza dell'immagine di output in pixel. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Recupera l'altezza dell'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Utilizza questa proprietà per impostare l'altezza dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà solo durante il rendering di un'unica immagine in HTML. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti questa proprietà, la proprietà viene ignorata.


**Returns:**
int - l'altezza dell'immagine di output in pixel.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Imposta l'altezza dell'immagine di output in pixel. Questo parametro si applica solo durante la conversione di un'unica immagine in HTML.


Utilizza questa proprietà per impostare l'altezza dell'immagine di output (in pixel). GroupDocs.Viewer applica questa proprietà solo durante il rendering di un'unica immagine in HTML. Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Se imposti questa proprietà, la proprietà viene ignorata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageHeight | int | L'altezza dell'immagine di output in pixel. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Recupera le opzioni di sicurezza per il documento PDF di output.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Imposta le opzioni di sicurezza per il documento PDF di output.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | Le opzioni di sicurezza per il documento PDF di output. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Recupera il callback usato per stimare l'avanzamento del salvataggio di un documento Words o Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - il callback per stimare l'avanzamento del salvataggio del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Imposta il callback usato per stimare l'avanzamento del salvataggio di un documento Words o Email.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Il callback per stimare l'avanzamento del salvataggio del documento. |
|

