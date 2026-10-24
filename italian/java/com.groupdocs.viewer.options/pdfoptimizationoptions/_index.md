---
title: "PdfOptimizationOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Utilizza questa classe per specificare le opzioni di ottimizzazione PDF da applicare al file PDF di output."
type: docs
weight: 21
url: /it/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Utilizza questa classe per specificare le opzioni di ottimizzazione PDF da applicare al file PDF di output.


Queste opzioni di ottimizzazione sono supportate per tutti i formati di file di input che sono supportati per l'esportazione in PDF.
Per dettagli e esempi di codice, vedere questa [pagina](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) e le relative pagine.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Imposta i valori predefiniti dell'opzione MaxResolution a 300 e dell'opzione ImageQuality a 100. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Abilita l'ottimizzazione del file PDF di output per la visualizzazione online con un browser web. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Imposta se ottimizzare il PDF di output per la navigazione online con un browser web. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Le annotazioni possono essere eliminate quando non sono necessarie. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Imposta se rimuovere le annotazioni non necessarie dal PDF. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Se il documento PDF contiene AcroForms, possiamo provare a ridurre le dimensioni del file appiattendo i campi del modulo. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Imposta se rimuovere i campi del modulo dal PDF. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | Il file PDF è composto da Testo, Immagine, Allegato, Annotazioni, Grafici e altri oggetti. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Imposta se convertire il PDF in scala di grigi. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Ogni carattere utilizzato per visualizzare il testo nella pagina contiene un insieme di glifi per i caratteri del font. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Imposta se sottogruppare i font nel PDF. |
|
|  | [isCompressImages()](#isCompressImages--) | Se il file PDF di origine contiene immagini, considera la compressione delle immagini e l'impostazione della loro qualità. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Imposta se comprimere le immagini nel PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | Se il file PDF di origine contiene immagini, considera la compressione delle immagini e l'impostazione della loro qualità. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Imposta la qualità dell'immagine per comprimere le immagini nel PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | Può essere usato con l'opzione CompressImages per ridimensionare le immagini a una risoluzione inferiore. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Imposta se ridimensionare le immagini nel PDF. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Può essere usato con l'opzione CompressImages per ridimensionare le immagini a una risoluzione inferiore. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Imposta la risoluzione massima per il ridimensionamento delle immagini nel PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Ottimizza i bordi e i caratteri dei fogli di calcolo Excel per ridurre la dimensione del file di output. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Imposta se ottimizzare i fogli di calcolo nel PDF. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Rimuove le informazioni private (informazioni sulla pagina) se impostato su true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Imposta se rimuovere le informazioni private dal PDF. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Se il documento utilizza caratteri incorporati, significa che tutti i dati dei caratteri sono inseriti nel documento. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Imposta se rimuovere l'incorporamento dei caratteri incorporati nel PDF. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | A volte un documento contiene diversi flussi di risorse identici (ad esempio immagini). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Imposta se collegare i flussi duplicati nel PDF. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Se questa proprietà è impostata su true, il contenuto della pagina verrà riutilizzato durante l'ottimizzazione del documento per pagine identiche. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Imposta se consentire il riutilizzo del contenuto della pagina nel PDF. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | A volte un documento contiene flussi di risorse inutilizzati. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Imposta se rimuovere i flussi inutilizzati dal PDF. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Un documento PDF a volte contiene gli oggetti PDF che non sono referenziati |
da nessun altro oggetto nel documento.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Imposta se rimuovere gli oggetti inutilizzati dal PDF. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Imposta i valori predefiniti dell'opzione MaxResolution a 300 e dell'opzione ImageQuality a 100.


Per dettagli e esempi di codice, vedere questa [pagina](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) e le relative pagine.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Abilita l'ottimizzazione del file PDF di output per la visualizzazione online con un browser web.


Per un esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  se il PDF di output è ottimizzato per la navigazione online,  false  altrimenti.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Imposta se ottimizzare il PDF di output per la navigazione online con un browser web.


Per un esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | linearize | boolean | true  per ottimizzare il PDF di output per la navigazione online,  false  altrimenti. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Le annotazioni possono essere eliminate quando non sono necessarie. Quando sono necessarie ma non richiedono ulteriori modifiche, possono essere appiattite. Ciò ridurrà la dimensione del file.


***Note:** The default value is 
false
.*
Per un esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  se le annotazioni sono rimosse,  false  altrimenti.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Imposta se rimuovere le annotazioni non necessarie dal PDF.


***Note:** The default value is 
false
.*
Per un esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  per rimuovere annotazioni non necessarie,  false  altrimenti. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Se il documento PDF contiene AcroForms, possiamo provare a ridurre le dimensioni del file appiattendo i campi del modulo.


***Note:** The default value is 
false
.*
Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  se i campi del modulo sono rimossi,  false  altrimenti.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Imposta se rimuovere i campi del modulo dal PDF.


***Note:** The default value is 
false
.*
Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removeFormFields | boolean | true  per rimuovere i campi del modulo,  false  altrimenti. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Il file PDF è composto da Testo, Immagine, Allegato, Annotazioni, Grafici e altri oggetti.
Potresti incontrare la necessità di convertire un PDF dallo spazio colore RGB a scala di grigi in modo che la stampa di questi file PDF sia più veloce.
Inoltre, quando il file viene convertito in scala di grigi, le dimensioni del documento si riducono, ma con questa modifica la qualità del documento potrebbe diminuire.
Attualmente, questa funzionalità è supportata dalla funzione Pre-Flight di Adobe Acrobat.


***Note:** The default value is 
false
.*
Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  se il PDF è convertito in scala di grigi,  false  altrimenti.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Imposta se convertire il PDF in scala di grigi.


***Note:** The default value is 
false
.*
Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  per convertire il PDF in scala di grigi,  false  altrimenti. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Ogni carattere utilizzato per visualizzare il testo nella pagina contiene un insieme di glifi per i caratteri del font.
La specifica PDF supporta il "sottoinsieme di font", ovvero font con solo i glifi effettivamente utilizzati.
Ciò può causare problemi quando il testo deve essere aggiornato (poiché probabilmente i glifi necessari sono assenti nel font), ma per i documenti che non si prevede di modificare ciò consente di ridurre le dimensioni.


***Note:** The default value is 
false
.*
Se il file utilizza font incorporati, contiene tutti i dati del font. GroupDocs.Viewer può creare sottoinsiemi di font incorporati per ridurre la dimensione del file. Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  se i font sono sottoposti a sottoinsieme,  false  altrimenti.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Imposta se sottogruppare i font nel PDF.


***Note:** The default value is 
false
.*
Se il file utilizza font incorporati, contiene tutti i dati del font. GroupDocs.Viewer può creare sottoinsiemi di font incorporati per ridurre la dimensione del file. Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | subsetFonts | boolean | true  per creare un sottoinsieme dei font,  false  altrimenti. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Se il file PDF di origine contiene immagini, considera la compressione delle immagini e l'impostazione della loro qualità.
Per abilitare la compressione delle immagini, impostare questa opzione su true. Tutte le immagini in un documento verranno ricomprese.
La compressione è definita dalla proprietà ImageQuality, che rappresenta il valore della qualità in percentuale.
Il 100% corrisponde a qualità invariata. Per ridurre la qualità dell'immagine, impostare la proprietà ImageQuality a un valore inferiore a 100.


***Note:** The default value is 
false
.*
Usa questa opzione per consentire altre opzioni di compressione: #setImageQuality(int).setImageQuality(int) e . Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  se le immagini sono compresse,  false  altrimenti.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Imposta se comprimere le immagini nel PDF.


***Note:** The default value is 
false
.*
Usa questa opzione per consentire altre opzioni di compressione: #setImageQuality(int).setImageQuality(int) e . Per l'esempio di codice, vedere questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | compressImages | boolean | true  per comprimere le immagini,  false  altrimenti. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Se il file PDF di origine contiene immagini, considera la compressione delle immagini e l'impostazione della loro qualità. Per abilitare la compressione delle immagini, imposta l'opzione CompressImages su true. Tutte le immagini in un documento saranno ricomprese. La compressione è definita dalla proprietà ImageQuality, che è il valore della qualità in percentuale. Il 100% corrisponde a qualità invariata. Per diminuire la qualità dell'immagine, imposta l'opzione CompressImages su true e la proprietà ImageQuality a un valore inferiore a 100.

<br />


***Note:** The default value is 
100
.*
Per modificare la qualità dell'immagine, imposta prima la proprietà #setCompressImages(boolean).setCompressImages(boolean) su true. Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - la qualità dell'immagine (valore compreso tra 1 e 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Imposta la qualità dell'immagine per comprimere le immagini nel PDF.


***Note:** The default value is 
100
.*
Per modificare la qualità dell'immagine, imposta prima la proprietà #setCompressImages(boolean).setCompressImages(boolean) su true. Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageQuality | int | la qualità dell'immagine (valore compreso tra 1 e 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Può essere usato con l'opzione CompressImages per ridimensionare le immagini a una risoluzione inferiore.
In questo caso, dovremmo impostare CompressImage su true, ResizeImages su true e MaxResolution al valore appropriato.


***Note:** The default value is 
false
.*
Per consentire questa opzione, imposta la proprietà su true. Questa opzione consente di impostare la proprietà. Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  se le immagini sono ridimensionate,  false  altrimenti.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Imposta se ridimensionare le immagini nel PDF.


***Note:** The default value is 
false
.*
Per consentire questa opzione, imposta la proprietà su true. Questa opzione consente di impostare la proprietà. Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | resizeImages | boolean | true  per ridimensionare le immagini,  false  altrimenti. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Può essere usato con l'opzione CompressImages per ridimensionare le immagini con una risoluzione inferiore. In questo caso, dovremmo impostare CompressImage su true, ResizeImages su true e MaxResolution al valore appropriato.


***Note:** The default value is 
300
.*
Per consentire questa opzione, imposta le proprietà #setCompressImages(boolean).setCompressImages(boolean) e #setMaxResolution(int).setMaxResolution(int) su true.
Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - la risoluzione massima per le immagini.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Imposta la risoluzione massima per il ridimensionamento delle immagini nel PDF.


***Note:** The default value is 
300
.*
Per consentire questa opzione, imposta le proprietà #setCompressImages(boolean).setCompressImages(boolean) e #setMaxResolution(int).setMaxResolution(int) su true.
Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxResolution | int | la risoluzione massima per le immagini. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Ottimizza i bordi e i caratteri dei fogli di calcolo Excel per ridurre la dimensione del file di output.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  se i fogli di calcolo sono ottimizzati,  false  altrimenti.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Imposta se ottimizzare i fogli di calcolo nel PDF.


Per un esempio di codice, vedi questa [documentazione](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  per ottimizzare i fogli di calcolo,  false  altrimenti. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Rimuove le informazioni private (informazioni sulla pagina) se impostato su true.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se le informazioni private sono rimosse,  false  altrimenti.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Imposta se rimuovere le informazioni private dal PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  per rimuovere le informazioni private,  false  altrimenti. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Se il documento utilizza caratteri incorporati, significa che tutti i dati dei caratteri sono inseriti nel documento.
L vantaggio è che il documento è visualizzabile indipendentemente dal fatto che il carattere sia installato sulla macchina dell\\u2019utente o meno. Ma l'incorporamento dei caratteri rende il documento più grande.
Il metodo unembed fonts rimuove tutti i caratteri incorporati. Questo diminuisce la dimensione del documento ma il documento potrebbe diventare illeggibile se il carattere corretto non è installato.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se i caratteri incorporati sono rimossi,  false  altrimenti.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Imposta se rimuovere l'incorporamento dei caratteri incorporati nel PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | unembedFonts | boolean | true  per rimuovere l'incorporamento dei caratteri incorporati,  false  altrimenti. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


A volte un documento contiene diversi flussi di risorse identici (ad esempio immagini).
Ciò può accadere, ad esempio, quando un documento è concatenato con se stesso.
Il documento di output contiene due copie indipendenti dello stesso flusso di risorse.
Analizziamo tutti i flussi di risorse e li confrontiamo. Se i flussi sono duplicati vengono uniti, cioè rimane solo una copia, i riferimenti vengono modificati in modo appropriato e le copie dell'oggetto vengono rimosse.
A volte questo diminuisce la dimensione del documento.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se i flussi duplicati sono collegati,  false  altrimenti.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Imposta se collegare i flussi duplicati nel PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  per collegare i flussi duplicati,  false  altrimenti. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Se questa proprietà è impostata su true, il contenuto della pagina verrà riutilizzato durante l'ottimizzazione del documento per pagine identiche.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se il contenuto della pagina è riutilizzato,  false  altrimenti.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Imposta se consentire il riutilizzo del contenuto della pagina nel PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  per consentire il riutilizzo del contenuto della pagina,  false  altrimenti. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


A volte un documento contiene flussi di risorse inutilizzati.
Questi flussi non sono \\u201coggetti inutilizzati\\u201d perché sono referenziati dal dizionario delle risorse della pagina\\u2019s.
Ciò può accadere nei casi in cui un'immagine è stata rimossa dalla pagina ma non dalle risorse della pagina.
Inoltre, questa situazione si verifica spesso quando le pagine vengono estratte dal documento e le pagine del documento hanno \\u201ccomuni\\u201d risorse,
cioè, lo stesso oggetto Resources. I contenuti della pagina vengono analizzati per determinare se un flusso di risorse
è utilizzato o meno. I flussi inutilizzati vengono rimossi. A volte questo diminuisce la dimensione del documento.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se i flussi inutilizzati vengono rimossi,  false  altrimenti.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Imposta se rimuovere i flussi inutilizzati dal PDF.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  per rimuovere i flussi inutilizzati,  false  altrimenti. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Un documento PDF a volte contiene gli oggetti PDF che non sono referenziati
da qualsiasi altro oggetto nel documento. Questo può accadere, ad esempio,
quando una pagina viene rimossa dall'albero delle pagine del documento ma l'oggetto pagina stesso non è rimosso.
Rimuovere questi oggetti non rende il documento non valido, ma lo riduce.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se gli oggetti inutilizzati vengono rimossi,  false  altrimenti.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Imposta se rimuovere gli oggetti inutilizzati dal PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  per rimuovere gli oggetti inutilizzati,  false  altrimenti. |
|

