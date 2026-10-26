---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce opzioni per il rendering di documenti in formato HTML."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Fornisce opzioni per il rendering di documenti in formato HTML.

La classe HtmlViewOptions racchiude impostazioni e parametri aggiuntivi che possono essere usati per controllare il rendering dei documenti in formato HTML nel componente GroupDocs.Viewer.

Per i dettagli, vedere il [topic][] e i suoi figli.

Esempio di utilizzo:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Campi

| Campo | Descrizione |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Determina se il rendering responsivo è abilitato. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Imposta se il rendering responsivo è abilitato. |
| [isMinify()](#isMinify--) | Verifica se la minificazione del contenuto HTML e delle risorse HTML è abilitata. |
| [setMinify(boolean value)](#setMinify-boolean-) | Imposta se la minificazione del contenuto HTML e delle risorse HTML è abilitata. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Abilita il rendering di un intero documento in un unico file HTML. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Abilita il rendering di un intero documento in un unico file HTML. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Restituisce la larghezza massima di un'immagine di output in pixel. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Imposta la larghezza massima di un'immagine di output in pixel. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Ottiene l'altezza massima di un'immagine di output in pixel. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Imposta l'altezza massima di un'immagine di output in pixel. |
| [getImageWidth()](#getImageWidth--) | Ottiene la larghezza dell'immagine di output in pixel. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Imposta la larghezza dell'immagine di output in pixel. |
| [getImageHeight()](#getImageHeight--) | Ottiene l'altezza dell'immagine di output in pixel durante la conversione di un'unica immagine in HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Imposta l'altezza dell'immagine di output in pixel durante la conversione di un'unica immagine in HTML. |
| [isForPrinting()](#isForPrinting--) | Verifica se l'HTML di output deve essere ottimizzato per la stampa. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Imposta se l'HTML di output deve essere ottimizzato per la stampa. |
| [isExcludeFonts()](#isExcludeFonts--) | Determina se escludere i font dal documento HTML. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Imposta se escludere i font dal documento HTML. |
| [getFontsToExclude()](#getFontsToExclude--) | Recupera l'elenco dei nomi dei font da escludere dal documento HTML. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Imposta l'elenco dei nomi dei font da escludere dal documento HTML. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Consente di rimuovere il codice sorgente JavaScript dai collegamenti nei documenti HTML risultanti, durante il rendering dei documenti di input che contengono gli script. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Imposta l'autorizzazione a rimuovere il codice sorgente JavaScript dai collegamenti nei documenti HTML risultanti, durante il rendering dei documenti di input che contengono gli script. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Recupera la callback utilizzata per stimare l'avanzamento del salvataggio di un documento Words o Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Imposta la callback utilizzata per stimare l'avanzamento del salvataggio di un documento Words o Email. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Inizializza una nuova istanza della classe  HtmlViewOptions . |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Inizializza una nuova istanza della classe  HtmlViewOptions . |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Inizializza una nuova istanza della classe  HtmlViewOptions . |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne. |
| [forExternalResources()](#forExternalResources--) | Inizializza una nuova istanza della classe  HtmlViewOptions . |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe  HtmlViewOptions . |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Determina se il rendering responsivo è abilitato. Le pagine web responsive vengono visualizzate correttamente su dispositivi con diverse dimensioni dello schermo.

Il design responsivo mira a far sì che le pagine web vengano visualizzate correttamente su una varietà di dispositivi. Per renderizzare con un layout responsivo, imposta questa proprietà su true. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolean -  true  se il rendering responsivo è abilitato,  false  altrimenti.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Imposta se il rendering responsivo è abilitato. Le pagine web responsive vengono visualizzate correttamente su dispositivi con diverse dimensioni dello schermo.

Il design responsivo mira a far sì che le pagine web vengano visualizzate correttamente su una varietà di dispositivi. Per renderizzare con un layout responsivo, imposta questa proprietà su true. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | true  per abilitare il rendering responsivo,  false  per disabilitarlo. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Verifica se la minificazione del contenuto HTML e delle risorse HTML è abilitata.

La compressione del contenuto di output (HTML, CSS e SVG) è uno dei modi per ottimizzare il file HTML. Per farlo, imposta questa proprietà su true. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  se la minificazione è abilitata,  false  altrimenti.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Imposta se la minificazione del contenuto HTML e delle risorse HTML è abilitata.

La compressione del contenuto di output (HTML, CSS e SVG) è uno dei modi per ottimizzare il file HTML. Per farlo, imposta questa proprietà su true. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | true  per abilitare la minificazione,  false  per disabilitarla. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Abilita il rendering di un intero documento in un unico file HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Abilita il rendering di un intero documento in un unico file HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Restituisce la larghezza massima di un'immagine di output in pixel.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la larghezza massima di un'immagine di output.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Imposta la larghezza massima di un'immagine di output in pixel.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageMaxWidth | int | La larghezza massima di un'immagine di output. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Ottiene l'altezza massima di un'immagine di output in pixel.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - l'altezza massima di un'immagine di output.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Imposta l'altezza massima di un'immagine di output in pixel.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageMaxHeight | int | L'altezza massima di un'immagine di output. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Ottiene la larghezza dell'immagine di output in pixel.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - la larghezza dell'immagine di output.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Imposta la larghezza dell'immagine di output in pixel.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageWidth | int | La larghezza dell'immagine di output. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Ottiene l'altezza dell'immagine di output in pixel durante la conversione di un'unica immagine in HTML.

Per dettagli ed esempi di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - l'altezza dell'immagine di output in pixel.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Imposta l'altezza dell'immagine di output in pixel durante la conversione di un'unica immagine in HTML.

Per dettagli ed esempi di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageHeight | int | L'altezza dell'immagine di output in pixel. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Verifica se l'HTML di output deve essere ottimizzato per la stampa.

Abilita questa opzione per convertire le pagine HTML di output nel formato SVG vettoriale. Per dettagli ed esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  se l'HTML di output deve essere ottimizzato per la stampa,  false  altrimenti.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Imposta se l'HTML di output deve essere ottimizzato per la stampa.

Abilita questa opzione per convertire le pagine HTML di output nel formato SVG vettoriale. Per dettagli ed esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | true  per ottimizzare l'HTML di output per la stampa,  false  altrimenti. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Determina se escludere i font dal documento HTML.

Per impostazione predefinita, GroupDocs.Viewer incorpora i caratteri utilizzati nel documento nell'HTML. Per evitarlo, imposta questa proprietà su true. Per dettagli ed esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  se i caratteri devono essere esclusi,  false  altrimenti.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Imposta se escludere i font dal documento HTML.

Per impostazione predefinita, GroupDocs.Viewer incorpora i caratteri utilizzati nel documento nell'HTML. Per evitarlo, imposta questa proprietà su true. Per dettagli ed esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | true  per escludere i caratteri,  false  altrimenti. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Recupera l'elenco dei nomi dei font da escludere dal documento HTML.

Questa opzione è supportata solo per le presentazioni. Includere i caratteri nel documento HTML migliora la stabilità della visualizzazione di output ma aumenta la dimensione del risultato del rendering. Usa questa opzione per trovare un compromesso tra stabilità e dimensione dell'output. Includi i nomi dei caratteri più diffusi e installati sulla maggior parte dei sistemi.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - l'elenco dei nomi dei caratteri da escludere dal documento HTML.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Imposta l'elenco dei nomi dei font da escludere dal documento HTML.

Questa opzione è supportata solo per le presentazioni. Includere i caratteri nel documento HTML migliora la stabilità della visualizzazione di output ma aumenta la dimensione del risultato del rendering. Usa questa opzione per trovare un compromesso tra stabilità e dimensione dell'output. Includi i nomi dei caratteri più diffusi e installati sulla maggior parte dei sistemi.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | L'elenco dei nomi dei caratteri da escludere dal documento HTML. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Consente di rimuovere il codice sorgente JavaScript dai collegamenti nei documenti HTML risultanti, durante il rendering dei documenti di input che contengono script. Per impostazione predefinita è abilitato (true).

Per dettagli sulla rimozione di JavaScript, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Imposta il permesso di rimuovere il codice sorgente JavaScript dai collegamenti nei documenti HTML risultanti, durante il rendering dei documenti di input che contengono script. Per impostazione predefinita è abilitato (true).

Per dettagli sulla rimozione di JavaScript, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Recupera la callback utilizzata per stimare l'avanzamento del salvataggio di un documento Words o Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - il callback usato per stimare l'avanzamento del salvataggio del documento.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Imposta la callback utilizzata per stimare l'avanzamento del salvataggio di un documento Words o Email.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Il callback usato per stimare l'avanzamento del salvataggio del documento. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate.

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Il metodo che rilascia lo stream creato dal metodo assegnato al parametro  createPageStream . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse incorporate.

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Inizializza una nuova istanza della classe  HtmlViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Inizializza una nuova istanza della classe  HtmlViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad esempio 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Inizializza una nuova istanza della classe  HtmlViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Il formato del percorso file, ad esempio 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Il metodo che rilascia lo stream creato dal metodo  createPageStream . |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Il metodo che crea l'URL per la risorsa HTML. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne.

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della risorsa HTML di output. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Il metodo che crea l'URL per la risorsa HTML. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Il metodo che rilascia lo stream creato dal metodo  createPageStream . |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Il metodo che rilascia lo stream creato dal metodo  createResourceStream . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Inizializza una nuova istanza della classe  HtmlViewOptions  per il rendering in HTML con risorse esterne.

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | La factory che implementa i metodi per creare URL delle risorse e istanziare/rilasciare lo stream della risorsa HTML di output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Inizializza una nuova istanza della classe  HtmlViewOptions .

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

I file di output saranno collocati nella directory di lavoro corrente dell'applicazione. Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Inizializza una nuova istanza della classe  HtmlViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad esempio 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Il formato del percorso file della risorsa, ad esempio 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Il formato dell'URL della risorsa, ad esempio 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
