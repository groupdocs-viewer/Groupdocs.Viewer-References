---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce opzioni per il rendering di documenti in formato PNG."
type: docs
weight: 25
url: /it/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Fornisce opzioni per il rendering di documenti in formato PNG.

La classe PngViewOptions incapsula impostazioni e parametri aggiuntivi che possono essere usati per controllare il rendering dei documenti in formato PNG nel componente GroupDocs.Viewer.

Esempio di utilizzo:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inizializza una nuova istanza della classe  PngViewOptions . |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inizializza una nuova istanza della classe  PngViewOptions . |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inizializza una nuova istanza della classe  PngViewOptions . |
| [PngViewOptions()](#PngViewOptions--) | Inizializza una nuova istanza della classe  PngViewOptions . |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Inizializza una nuova istanza della classe  PngViewOptions . |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Inizializza una nuova istanza della classe  PngViewOptions . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Restituisce la larghezza massima di un'immagine di output in pixel. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Imposta la larghezza massima di un'immagine di output in pixel. |
| [getMaxHeight()](#getMaxHeight--) | Restituisce l'altezza massima di un'immagine di output in pixel. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Imposta l'altezza massima di un'immagine di output in pixel. |
| [isExtractText()](#isExtractText--) | Determina se l'estrazione del testo è abilitata. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Abilita o disabilita l'estrazione del testo. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine di output in pixel. |
| [setWidth(int value)](#setWidth-int-) | Imposta la larghezza dell'immagine di output in pixel. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine di output in pixel. |
| [setHeight(int value)](#setHeight-int-) | Imposta l'altezza dell'immagine di output in pixel. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Recupera la callback per stimare l'avanzamento del salvataggio di un documento. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Imposta la callback per stimare l'avanzamento del salvataggio di un documento. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe  PngViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe  PngViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Il metodo che rilascia lo stream creato dal metodo assegnato al parametro createPageStream. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Inizializza una nuova istanza della classe  PngViewOptions .

Per l'esempio di codice, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Inizializza una nuova istanza della classe  PngViewOptions .

Questo costruttore inizializza una nuova istanza di  PngViewOptions  con \"p\\_\\{0\\}.png\" come formato del percorso file per i file di output. I file di output saranno collocati nella directory di lavoro corrente dell'applicazione. Per l'esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Inizializza una nuova istanza della classe  PngViewOptions .

Ad esempio, se il formato del percorso file è 'page\\_\\{0\\}.png', i file di output saranno denominati 'page\\_1.png', 'page\\_2.png', e così via, in base al numero di pagina.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es., 'page\\_\\{0\\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Inizializza una nuova istanza della classe  PngViewOptions .

Ad esempio, se il formato del percorso file è 'page\\_\\{0\\}.png', i file di output saranno denominati 'page\\_1.png', 'page\\_2.png', e così via, in base al numero di pagina. Per l'esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Il formato del percorso file, ad es., 'page\\_\\{0\\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Restituisce la larghezza massima di un'immagine di output in pixel.

Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti la  proprietà, questa proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - la larghezza massima dell'immagine di output.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Imposta la larghezza massima di un'immagine di output in pixel.

Usa questa proprietà per impostare la larghezza massima dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti la  proprietà, questa proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxWidth | int | La larghezza massima dell'immagine di output. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Restituisce l'altezza massima di un'immagine di output in pixel.

Usa questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti la  proprietà, questa proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - l'altezza massima dell'immagine di output.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Imposta l'altezza massima di un'immagine di output in pixel.

Usa questa proprietà per impostare l'altezza massima dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti la  proprietà, questa proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxHeight | int | L'altezza massima dell'immagine di output. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Determina se l'estrazione del testo è abilitata.

Questa opzione potrebbe essere utile quando desideri aggiungere uno strato di testo selezionabile sull'immagine. Usa questa proprietà per ottenere il testo contenuto in un documento sorgente e le sue coordinate. Quindi puoi utilizzare questi dati per aggiungere un testo selezionabile sull'immagine o per implementare una ricerca di testo nella resa basata su immagine. Per l'esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  se l'estrazione del testo è abilitata,  false  altrimenti.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Abilita o disabilita l'estrazione del testo.

Questa opzione potrebbe essere utile quando desideri aggiungere uno strato di testo selezionabile sull'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | true  per abilitare l'estrazione del testo,  false  per disabilitarla. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza dell'immagine di output in pixel.

Usa questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti questa proprietà, la  proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - la larghezza dell'immagine di output.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza dell'immagine di output in pixel.

Usa questa proprietà per impostare la larghezza dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti questa proprietà, la  proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | La larghezza dell'immagine di output. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza dell'immagine di output in pixel.

Usa questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti questa proprietà, la  proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - l'altezza dell'immagine di output.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza dell'immagine di output in pixel.

Usa questa proprietà per impostare l'altezza dell'immagine di output (in pixel). Per l'esempio di codice, vedere la [documentazione][]. Se imposti questa proprietà, la  proprietà viene ignorata.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | L'altezza dell'immagine di output. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Recupera la callback per stimare l'avanzamento del salvataggio di un documento.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - il callback per stimare l'avanzamento del salvataggio del documento.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Imposta la callback per stimare l'avanzamento del salvataggio di un documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Il callback per stimare l'avanzamento del salvataggio del documento. |

