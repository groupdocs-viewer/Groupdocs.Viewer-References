---
title: "WordProcessingOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei documenti di elaborazione testi."
type: docs
weight: 38
url: /it/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Fornisce opzioni per il rendering dei documenti di elaborazione testi.


La classe WordProcessingOptions fornisce opzioni per il rendering dei documenti di elaborazione testi
nel componente GroupDocs.Viewer. Incapsula impostazioni e parametri che possono essere utilizzati
per controllare il processo di rendering e il formato di output per i file di elaborazione testi.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Esempio di utilizzo:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Inizializza una nuova istanza di |
WordProcessingOptions
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Recupera la dimensione della pagina per il rendering dei file HTM e HTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Imposta la dimensione della pagina per il rendering dei file HTM e HTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indica se il rendering delle modifiche tracciate (revisioni) è abilitato. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Imposta se il rendering delle modifiche tracciate (revisioni) è abilitato. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Recupera il margine sinistro della pagina per il rendering HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Imposta il margine sinistro della pagina per il rendering HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | Recupera il margine destro della pagina per il rendering HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Imposta il margine destro della pagina per il rendering HTML. |
|
|  | [getTopMargin()](#getTopMargin--) | Recupera il margine superiore della pagina per il rendering HTML. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Imposta il margine superiore della pagina per il rendering HTML. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Margine inferiore della pagina (solo per il rendering HTML) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Imposta il margine inferiore della pagina per il rendering HTML. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Questa opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani, basati su latino o basati su cirillico. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Questa opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani, basati su latino o basati su cirillico. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indica se la navigazione del sommario deve essere disabilitata durante il rendering in HTML o PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Imposta se la navigazione del sommario deve essere disabilitata durante il rendering in HTML o PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Ottiene un valore che determina se i campi di determinati tipi devono essere aggiornati prima di salvare il documento WordProcessing di input nei formati di output HTML, PDF, PNG o JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Imposta un valore che determina se i campi di determinati tipi devono essere aggiornati prima di salvare il documento WordProcessing di input nei formati di output HTML, PDF, PNG o JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene la risoluzione orizzontale per le immagini generate in punti per pollice. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Imposta la risoluzione orizzontale per le immagini generate in punti per pollice. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Ottiene la risoluzione verticale per le immagini generate in punti per pollice. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Imposta la risoluzione verticale per le immagini generate in punti per pollice. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Consente di applicare forzatamente la numerazione delle pagine al documento WordProcessing caricato. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Consente di applicare forzatamente la numerazione delle pagine al documento WordProcessing caricato. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Verifica se le opzioni sono state modificate. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Inizializza una nuova istanza di
WordProcessingOptions
classe.
Contiene le opzioni per il rendering dei documenti di elaborazione testi. Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Recupera la dimensione della pagina per il rendering dei file HTM e HTML.


Quando si utilizza la dimensione di pagina predefinita, alcuni contenuti potrebbero non adattarsi al riquadro della pagina.
Per adattare i contenuti, è possibile impostare una dimensione di pagina più grande, come A3, utilizzando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Imposta la dimensione della pagina per il rendering dei file HTM e HTML.


Quando si utilizza la dimensione di pagina predefinita, alcuni contenuti potrebbero non adattarsi al riquadro della pagina.
Per adattare i contenuti, è possibile impostare una dimensione di pagina più grande, come A3, utilizzando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La dimensione della pagina di output. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indica se il rendering delle modifiche tracciate (revisioni) è abilitato.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  se il rendering delle modifiche tracciate è abilitato,  false  altrimenti.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Imposta se il rendering delle modifiche tracciate (revisioni) è abilitato.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il rendering delle modifiche tracciate,  false  per disabilitarlo. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Recupera il margine sinistro della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - il valore del margine sinistro della pagina.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Imposta il margine sinistro della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Il valore del margine sinistro della pagina da impostare. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Recupera il margine destro della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - il valore del margine destro della pagina.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Imposta il margine destro della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Il valore del margine destro della pagina da impostare. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Recupera il margine superiore della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - il margine superiore della pagina.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Imposta il margine superiore della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Il margine superiore della pagina da impostare. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Margine inferiore della pagina (solo per il rendering HTML)
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - il margine inferiore della pagina.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Imposta il margine inferiore della pagina per il rendering HTML.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Il margine inferiore della pagina da impostare. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Questa opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani, basati su latino o basati su cirillico.


**Returns:**
boolean - True se le funzionalità OpenType sono abilitate, false altrimenti.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Questa opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani, basati su latino o basati su cirillico.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | True per abilitare le funzionalità OpenType, false altrimenti. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indica se la navigazione del sommario deve essere disabilitata durante il rendering in HTML o PDF. Quando questa opzione è impostata su true, per il rendering HTML i collegamenti relativi del sommario verranno sostituiti con tag span, rimuovendo la funzionalità ma mantenendo l'aspetto visivo. Per il rendering PDF, il sommario verrà renderizzato come testo semplice senza collegamenti.


**Returns:**
boolean - True se la navigazione del sommario è disabilitata; altrimenti, false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Imposta se la navigazione del sommario deve essere disabilitata durante il rendering in HTML o PDF. Quando questa opzione è impostata su true, per il rendering HTML i collegamenti relativi del sommario verranno sostituiti con tag span, rimuovendo la funzionalità ma mantenendo l'aspetto visivo. Per il rendering PDF, il sommario verrà renderizzato come testo semplice senza collegamenti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Indica se la navigazione del sommario deve essere disabilitata. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Restituisce un valore che determina se i campi di determinati tipi devono essere aggiornati prima di salvare il documento WordProcessing di input nei formati di output HTML, PDF, PNG o JPEG. Il valore predefinito per questa proprietà è true \\u2014 i campi verranno aggiornati prima del salvataggio.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Imposta un valore che determina se i campi di determinati tipi devono essere aggiornati prima di salvare il documento WordProcessing di input nei formati di output HTML, PDF, PNG o JPEG. Il valore predefinito per questa proprietà è true \\u2014 i campi verranno aggiornati prima del salvataggio.


Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Restituisce la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Returns:**
int - la risoluzione orizzontale in DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Imposta la risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG.


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


Restituisce la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Returns:**
int - la risoluzione verticale in DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Imposta la risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG.


Il valore predefinito è 96 DPI. Valore minimo possibile - 72 DPI, valore massimo possibile - 600 DPI.
Se il valore specificato dall'utente è fuori da questi limiti, verrà applicato il valore minimo o massimo possibile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | verticalResolution | int | la risoluzione verticale in DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Consente di applicare forzatamente la numerazione delle pagine al documento WordProcessing caricato. Per impostazione predefinita è [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 il documento rimane intatto.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Consente di applicare forzatamente la numerazione delle pagine al documento WordProcessing caricato. Per impostazione predefinita è [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 il documento rimane intatto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | la posizione del numero di pagina. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se le opzioni sono state modificate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | o | java.lang.Object | L'oggetto da confrontare per uguaglianza. |
|

**Returns:**
boolean -  true  se le opzioni sono uguali all'oggetto specificato,  false  altrimenti.

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

