---
title: "PdfOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni per il rendering dei documenti PDF."
type: docs
weight: 22
url: /it/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Fornisce opzioni per il rendering dei documenti PDF.


La classe PdfOptions incapsula varie impostazioni e parametri che possono essere utilizzati
per controllare il rendering dei documenti PDF nel componente GroupDocs.Viewer.
Per ulteriori dettagli, consulta la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Esempio di utilizzo:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Inizializza una nuova istanza di |
PdfOptions
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Disattiva la protezione contro la copia del contenuto durante il rendering in HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Disattiva la protezione contro la copia del contenuto durante il rendering in HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Determina se il testo della sorgente viene renderizzato come immagine in HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Imposta se il testo della sorgente viene renderizzato come immagine in HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Verifica se il raggruppamento dei caratteri è disabilitato per mantenere la massima precisione durante il posizionamento dei caratteri nel rendering della pagina. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Imposta l'opzione per disabilitare il raggruppamento dei caratteri, garantendo la massima precisione durante il posizionamento dei caratteri nel rendering della pagina. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Verifica se il rendering di testo e grafica deve seguire l'ordine Z nel documento PDF originale durante il rendering in HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Abilita o disabilita il rendering di testo e grafica secondo l'ordine z nel documento PDF originale durante il rendering in HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Determina se il hinting dei caratteri è abilitato. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Abilita il hinting dei caratteri. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Abilita il rendering delle pagine con le stesse dimensioni in pixel della dimensione della pagina nel documento PDF di origine. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Abilita il rendering delle pagine con le stesse dimensioni in pixel della dimensione della pagina nel documento PDF di origine. |
|
|  | [getImageQuality()](#getImageQuality--) | Recupera la qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Imposta la qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF è un formato fisso, quindi tutti gli elementi hanno una posizione specifica su una pagina. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF è un formato fisso, quindi tutti gli elementi hanno una posizione specifica su una pagina. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Abilita questa opzione per avvolgere ogni immagine nel documento HTML di output con il tag SVG per migliorare la qualità dell'output. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Abilita questa opzione per avvolgere ogni immagine nel documento HTML di output con il tag SVG per migliorare la qualità dell'output. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Sostituisce i caratteri tipografici, se necessario, per garantire che tutti i caratteri nel testo possano essere visualizzati. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Sostituisce i caratteri tipografici, se necessario, per garantire che tutti i caratteri nel testo possano essere visualizzati. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Disabilita eventuali restrizioni di licenza per tutti i caratteri nel documento XPS/OXPS corrente. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Imposta il flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri nel documento XPS/OXPS corrente. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Inizializza una nuova istanza di
PdfOptions
classe.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Disattiva la protezione contro la copia del contenuto durante il rendering in HTML.


Durante il rendering di file PDF con protezione contro la copia di testo e immagini in HTML, GroupDocs.Viewer aggiunge un attributo HTML 'inert' al tag BODY dell'HTML.
Il valore predefinito di questa opzione è
false
.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Disattiva la protezione contro la copia del contenuto durante il rendering in HTML.


Durante il rendering di file PDF con protezione contro la copia di testo e immagini in HTML, GroupDocs.Viewer aggiunge un attributo HTML 'inert' al tag BODY dell'HTML.
Il valore predefinito di questa opzione è
false
.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Determina se il testo della sorgente viene renderizzato come immagine in HTML.


Quando questa opzione è impostata su
true
, il testo viene renderizzato come immagine nell'HTML di output.
Abilita questa opzione per rendere il testo non selezionabile o per correggere il rendering dei caratteri e far apparire l'HTML come un PDF.
Questa opzione è supportata durante il rendering in HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  se il testo è renderizzato come immagine in HTML,  false  altrimenti.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Imposta se il testo della sorgente viene renderizzato come immagine in HTML.


Quando questa opzione è impostata su
true
, il testo viene renderizzato come immagine nell'HTML di output.
Abilita questa opzione per rendere il testo non selezionabile o per correggere il rendering dei caratteri e far apparire l'HTML come un PDF.
Questa opzione è supportata durante il rendering in HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  per rendere il testo come immagine in HTML,  false  altrimenti. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Verifica se il raggruppamento dei caratteri è disabilitato per mantenere la massima precisione durante il posizionamento dei caratteri nel rendering della pagina.
Quando questa opzione è abilitata, i caratteri vengono renderizzati senza alcun raggruppamento, garantendo la massima precisione.


***Note:** By default, character grouping is enabled.*
Durante la conversione dei file PDF, GroupDocs.Viewer raggruppa i singoli caratteri in parole per migliorare le prestazioni di rendering. Se il tuo documento contiene geroglifici o simboli speciali, potresti voler proibire il raggruppamento dei caratteri per garantire un layout più preciso. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  se il raggruppamento dei caratteri è disabilitato,  false  altrimenti.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Imposta l'opzione per disabilitare il raggruppamento dei caratteri, garantendo la massima precisione durante il posizionamento dei caratteri nel rendering della pagina.
Quando questa opzione è abilitata impostando il valore a
true
, il raggruppamento dei caratteri è disabilitato, garantendo la massima precisione.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Durante la conversione dei file PDF, GroupDocs.Viewer raggruppa i singoli caratteri in parole per migliorare le prestazioni di rendering. Se il tuo documento contiene geroglifici o simboli speciali, potresti voler proibire il raggruppamento dei caratteri per garantire un layout più preciso. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per disabilitare il raggruppamento dei caratteri,  false  per abilitarlo. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Verifica se il rendering di testo e grafica deve seguire l'ordine Z nel documento PDF originale durante il rendering in HTML.
Quando questa opzione è abilitata restituendo
true
, testo e grafica vengono renderizzati secondo il loro ordine Z nel documento PDF originale.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Per impostazione predefinita, GroupDocs.Veiewer renderizza testo e grafica come un unico livello in HTML. Questa opzione consente di disporre gli oggetti nello stesso ordine del file sorgente. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  se il rendering a più livelli è abilitato,  false  altrimenti.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Abilita o disabilita il rendering di testo e grafica secondo l'ordine z nel documento PDF originale durante il rendering in HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Per impostazione predefinita, GroupDocs.Veiewer renderizza testo e grafica come un unico livello in HTML. Questa opzione consente di disporre gli oggetti nello stesso ordine del file sorgente. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il rendering a più livelli,  false  per disabilitarlo. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Determina se il hinting dei font è abilitato. Il hinting dei font regola la visualizzazione di un font contorno.
Questa opzione è supportata solo per i font TrueType (TTF) quando utilizzati nel documento sorgente.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Il hinting dei font regola come viene visualizzato un font contorno. Applicabile solo ai font TTF usati nel documento sorgente. Questa opzione è disponibile per il rendering in formati PNG o JPG. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  se il hinting dei font è abilitato,  false  altrimenti.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Abilita il hinting dei font. Il hinting dei font regola la visualizzazione di un font contorno ed è supportato solo per i font TrueType (TTF) quando usati nel documento sorgente.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Il hinting dei font regola come viene visualizzato un font contorno. Applicabile solo ai font TTF usati nel documento sorgente. Questa opzione è disponibile per il rendering in formati PNG o JPG. Il valore predefinito è false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | true  per abilitare il hinting dei font,  false  per disabilitarlo. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Abilita il rendering delle pagine con le stesse dimensioni in pixel della dimensione della pagina nel documento PDF di origine.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Per impostazione predefinita, GroupDocs.Viewer calcola la dimensione della pagina immagine di output per una migliore qualità di rendering. Abilita questa opzione per garantire che le pagine di output abbiano la stessa dimensione della pagina del documento PDF sorgente (in pixel). Il valore predefinito è false.
Questa opzione è disponibile per il rendering in formati PNG o JPG.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  se l'opzione è abilitata,  false  altrimenti.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Abilita il rendering delle pagine con le stesse dimensioni in pixel della dimensione della pagina nel documento PDF di origine.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Per impostazione predefinita, GroupDocs.Viewer calcola la dimensione della pagina immagine di output per una migliore qualità di rendering. Abilita questa opzione per garantire che le pagine di output abbiano la stessa dimensione della pagina del documento PDF sorgente (in pixel). Il valore predefinito è false.
Questa opzione è disponibile per il rendering in formati PNG o JPG.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  per abilitare il rendering con la dimensione originale della pagina,  false  altrimenti. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Recupera la qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. Il valore predefinito è Low.


Quando questa opzione è impostata su true, GroupDocs.Viewer rende il testo come immagine nell'output HTML. Questo rende il testo non selezionabile e migliora il rendering dei caratteri, garantendo un aspetto simile a PDF in HTML. Il valore predefinito è false.
Questa opzione è disponibile per il rendering in HTML.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Imposta la qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. Il valore predefinito è Low.


Quando questa opzione è impostata su true, GroupDocs.Viewer rende il testo come immagine nell'output HTML. Questo rende il testo non selezionabile e migliora il rendering dei caratteri, garantendo un aspetto simile a PDF in HTML. Il valore predefinito è false.
Questa opzione è disponibile per il rendering in HTML.
Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | La qualità dell'immagine di output per le risorse immagine durante il rendering in HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF è un formato fisso, quindi tutti gli elementi hanno una posizione specifica su una pagina.
Per garantire che l'HTML di output abbia lo stesso aspetto del PDF di origine, i documenti vengono renderizzati in HTML con un layout fisso per impostazione predefinita.
Durante il rendering con layout fisso, l'HTML di output ha una dimensione fissa, quindi gli elementi rimarranno nello stesso posto indipendentemente dalla dimensione della finestra.
Per renderizzare in HTML con layout fluido, impostare questa proprietà su false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
I documenti PDF ed EPUB vengono inizialmente renderizzati in HTML con un layout fisso per mantenere l'aspetto del documento di origine. Questo layout fisso significa che tutti gli elementi HTML hanno posizioni precise all'interno di un contenitore con dimensioni impostate. Ridimensionare la finestra del browser non influisce sulla posizione e sulla dimensione degli elementi nel documento.
Questa opzione è disponibile solo durante il rendering in HTML. Il valore predefinito è true. Per renderizzare con un layout fluido, impostare questa proprietà su false.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true se è layout fisso

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF è un formato fisso, quindi tutti gli elementi hanno una posizione specifica su una pagina.
Per garantire che l'HTML di output abbia lo stesso aspetto del PDF di origine, i documenti vengono renderizzati in HTML con un layout fisso per impostazione predefinita.
Durante il rendering con layout fisso, l'HTML di output ha una dimensione fissa, quindi gli elementi rimarranno nello stesso posto indipendentemente dalla dimensione della finestra.
Per renderizzare in HTML con layout fluido, impostare questa proprietà su false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
I documenti PDF ed EPUB vengono inizialmente renderizzati in HTML con un layout fisso per mantenere l'aspetto del documento di origine. Questo layout fisso significa che tutti gli elementi HTML hanno posizioni precise all'interno di un contenitore con dimensioni impostate. Ridimensionare la finestra del browser non influisce sulla posizione e sulla dimensione degli elementi nel documento.
Questa opzione è disponibile solo durante il rendering in HTML. Il valore predefinito è true. Per renderizzare con un layout fluido, impostare questa proprietà su false.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fixedLayout | boolean | true se è layout fisso |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Abilita questa opzione per avvolgere ogni immagine nel documento HTML di output con il tag SVG per migliorare la qualità dell'output.


Questa opzione è supportata quando si renderizza [PDF e formati di file Layout di pagina](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) in HTML con risorse incorporate ed esterne.


Per impostazione predefinita, durante il rendering in file PDF e Layout di pagina, tutte le immagini vengono renderizzate come un'unica immagine PNG. L'immagine PNG renderizzata viene utilizzata come sfondo per il documento HTML di output.


Per saperne di più:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  se le immagini sono avvolte in SVG,  false  altrimenti.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Abilita questa opzione per avvolgere ogni immagine nel documento HTML di output con il tag SVG per migliorare la qualità dell'output.


Questa opzione è supportata quando si renderizza [PDF e formati di file Layout di pagina](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) in HTML con risorse incorporate ed esterne.


Per impostazione predefinita, durante il rendering in file PDF e Layout di pagina, tutte le immagini vengono renderizzate come un'unica immagine PNG. L'immagine PNG renderizzata viene utilizzata come sfondo per il documento HTML di output.


Per saperne di più:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  se le immagini devono essere avvolte in SVG,  false  altrimenti. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Sostituisce i caratteri tipografici, se necessario, per garantire che tutti i caratteri nel testo possano essere visualizzati.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Sostituisce i caratteri tipografici, se necessario, per garantire che tutti i caratteri nel testo possano essere visualizzati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | analyzeFonts | boolean | true se i font devono essere visualizzati, false altrimenti. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Disabilita eventuali restrizioni di licenza per tutti i caratteri nel documento XPS/OXPS corrente.


Molte operazioni con il carattere non possono essere eseguite se queste operazioni sono proibite dalla licenza di questo carattere.
Ad esempio, alcuni caratteri non possono essere incorporati in un documento PDF se le regole della licenza disabilitano l'incorporamento per questo carattere.
Fai attenzione quando usi questo flag. Quando è impostato, significa che la persona che imposta questo flag si assume tutta la responsabilità
per eventuali violazioni di licenza/legge su se stessi. Quindi lo assumono a proprio rischio. È fortemente consigliato utilizzare
questo flag solo quando sei completamente sicuro di non violare la legge sul diritto d'autore. Per impostazione predefinita false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Imposta il flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri nel documento XPS/OXPS corrente.


Molte operazioni con il carattere non possono essere eseguite se queste operazioni sono proibite dalla licenza di questo carattere.
Ad esempio, alcuni caratteri non possono essere incorporati in un documento PDF se le regole della licenza disabilitano l'incorporamento per questo carattere.
Fai attenzione quando usi questo flag. Quando è impostato, significa che la persona che imposta questo flag si assume tutta la responsabilità
per eventuali violazioni di licenza/legge su se stessi. Quindi lo assumono a proprio rischio. È fortemente consigliato utilizzare
questo flag solo quando sei completamente sicuro di non violare la legge sul diritto d'autore. Per impostazione predefinita false.
Per un esempio di codice, vedi la [documentazione](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

