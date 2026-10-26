---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Questa classe aiuta a personalizzare ."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Questa classe aiuta a personalizzare [Cache](../../com.groupdocs.viewer.caching/cache).

I modelli personalizzati per la serializzazione possono essere implementati sovrascrivendo i metodi in questa classe per restituirli al posto di quelli incorporati. Per ottenere ciò, estendi CacheableFactory e attivalo passando una nuova istanza della fabbrica personalizzata al metodo [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) .

Esempio di utilizzo:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

Per ulteriori dettagli, linee guida ed esempi sulla personalizzazione della cache, consultare la [documentazione di GroupDocs.Viewer][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInstance()](#getInstance--) | Ottiene un'istanza di  CacheableFactory  che può essere utilizzata per creare oggetti cacheabili. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Imposta l'istanza di  CacheableFactory  da utilizzare. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Crea un'implementazione dell'interfaccia [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) per il tipo di file e le pagine specificati. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crea un'implementazione dell'interfaccia [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) per il tipo di file, le pagine e il conteggio delle note specificati. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crea un'implementazione dell'interfaccia [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) per il tipo di file, le pagine e le cartelle specificati. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Crea un'implementazione dell'interfaccia [Character](../../com.groupdocs.viewer.results/character) per il carattere, la posizione e le dimensioni specificati. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Crea un'implementazione dell'interfaccia [FileInfo](../../com.groupdocs.viewer.results/fileinfo) per il tipo di file specificato. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Crea un'implementazione dell'interfaccia [Layer](../../com.groupdocs.viewer.results/layer) con il nome e la visibilità specificati. |
| [newLayer(String name)](#newLayer-java.lang.String-) | Crea un'implementazione dell'interfaccia [Layer](../../com.groupdocs.viewer.results/layer) con il nome specificato. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Crea un'implementazione dell'interfaccia [Layout](../../com.groupdocs.viewer.results/layout) con il nome, la larghezza e l'altezza specificati. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Crea un'implementazione dell'interfaccia [Line](../../com.groupdocs.viewer.results/line) con la linea, la posizione, le dimensioni e le parole specificate. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Crea un'implementazione dell'interfaccia [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basata sul tipo di file, l'elenco delle pagine e l'elenco delle cartelle specificati. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero e la visibilità specificati. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome e la visibilità specificati. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome, la visibilità, la larghezza e l'altezza specificati. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, la visibilità, la larghezza e l'altezza specificati. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome, la visibilità, la larghezza, l'altezza e le linee specificati. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, la visibilità, la larghezza, l'altezza e le linee specificati. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Crea un'implementazione dell'interfaccia [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) con il tipo di file, le pagine e il flag di stampa consentita specificati. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Crea un'implementazione dell'interfaccia [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) con il tipo di file, le pagine, i livelli e i layout specificati. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Crea un'implementazione dell'interfaccia [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) con il tipo di file, le pagine, la data di inizio e la data di fine specificati. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Crea un'implementazione dell'interfaccia [TextElement](../../com.groupdocs.viewer.results/textelement) con il valore, le coordinate e le dimensioni specificati. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Crea un'implementazione dell'interfaccia MboxViewInfo con il tipo di file, le pagine e il conteggio delle note specificati. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Crea un'implementazione dell'interfaccia [Word](../../com.groupdocs.viewer.results/word) con la parola, le coordinate, le dimensioni e i caratteri specificati. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Ottiene un'istanza di  CacheableFactory  che può essere utilizzata per creare oggetti cacheabili.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Imposta l'istanza di  CacheableFactory  da utilizzare. Questo consente un'implementazione personalizzata della factory cacheable.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | L'istanza di  CacheableFactory  da impostare. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Crea un'implementazione dell'interfaccia [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) per il tipo di file e le pagine specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine che rappresentano le pagine del documento. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crea un'implementazione dell'interfaccia [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) per il tipo di file, le pagine e il conteggio delle note specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine che rappresentano le pagine del documento. |
| notesCount | int | Il conteggio delle Lotus Notes nel documento. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crea un'implementazione dell'interfaccia [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) per il tipo di file, le pagine e le cartelle specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine che rappresentano le pagine del documento. |
| cartelle | java.util.List<java.lang.String> | L'elenco delle cartelle nell'archivio. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Crea un'implementazione dell'interfaccia [Character](../../com.groupdocs.viewer.results/character) per il carattere, la posizione e le dimensioni specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| carattere | char | Il carattere. |
| x | double | La coordinata x della posizione del carattere. |
| y | double | La coordinata y della posizione del carattere. |
| width | double | La larghezza del carattere. |
| height | double | L'altezza del carattere. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Crea un'implementazione dell'interfaccia [FileInfo](../../com.groupdocs.viewer.results/fileinfo) per il tipo di file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Crea un'implementazione dell'interfaccia [Layer](../../com.groupdocs.viewer.results/layer) con il nome e la visibilità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome del livello. |
| visibile | boolean | La visibilità del livello. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Crea un'implementazione dell'interfaccia [Layer](../../com.groupdocs.viewer.results/layer) con il nome specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome del livello. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Crea un'implementazione dell'interfaccia [Layout](../../com.groupdocs.viewer.results/layout) con il nome, la larghezza e l'altezza specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome del layout. |
| width | double | La larghezza del layout. |
| height | double | L'altezza del layout. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Crea un'implementazione dell'interfaccia [Line](../../com.groupdocs.viewer.results/line) con la linea, la posizione, le dimensioni e le parole specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| linea | java.lang.String | Il contenuto della linea. |
| x | double | La coordinata X del punto in alto a sinistra del rettangolo che contiene la linea. |
| y | double | La coordinata Y del punto in alto a sinistra del rettangolo che contiene la linea. |
| width | double | La larghezza del rettangolo che contiene la linea (in pixel). |
| height | double | L'altezza del rettangolo che contiene la linea (in pixel). |
| parole | java.util.List<com.groupdocs.viewer.results.Word> | Le parole contenute nella linea. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome dell'allegato. |
| filePath | java.lang.String | Il percorso relativo dell'allegato, ad esempio "folder/file.docx". Quando il file si trova nella radice di un archivio, in un messaggio email o in un file di dati, specificare il nome del file. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | java.lang.String | L'ID dell'allegato. |
| fileName | java.lang.String | Il nome dell'allegato. |
| filePath | java.lang.String | Il percorso relativo dell'allegato, ad esempio "folder/file.docx". Quando il file si trova nella radice di un archivio, in un messaggio email o in un file di dati, specificare il nome del file. |
| dimensione | long | La dimensione dell'allegato. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | java.lang.String | L'ID dell'allegato. |
| fileName | java.lang.String | Il nome dell'allegato. |
| filePath | java.nio.file.Path | Il percorso relativo o assoluto dell'allegato. |
| dimensione | long | La dimensione dell'allegato. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Crea un'implementazione dell'interfaccia [Attachment](../../com.groupdocs.viewer.results/attachment). L'allegato rappresenta un file allegato a un documento o a un messaggio di posta elettronica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | java.lang.String | L'ID dell'allegato. |
| fileName | java.lang.String | Il nome dell'allegato. |
| filePath | java.lang.String | Il percorso relativo o assoluto dell'allegato. Può essere un percorso file all'interno di una cartella o il nome del file stesso se il file si trova nella radice di un archivio, in un messaggio di posta elettronica o in un file di dati. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo del file allegato. |
| dimensione | long | La dimensione dell'allegato. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Crea un'implementazione dell'interfaccia [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) basata sul tipo di file, l'elenco delle pagine e l'elenco delle cartelle specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine. |
| cartelle | java.util.List<java.lang.String> | L'elenco delle cartelle. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero e la visibilità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| visibile | boolean | Il flag di visibilità. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome e la visibilità specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| nome | java.lang.String | Il nome della pagina. |
| visibile | boolean | Il flag di visibilità. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome, la visibilità, la larghezza e l'altezza specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| nome | java.lang.String | Il nome della pagina. |
| visibile | boolean | Il flag di visibilità. |
| width | int | La larghezza della pagina. |
| height | int | L'altezza della pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, la visibilità, la larghezza e l'altezza specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| visibile | boolean | Il flag di visibilità. |
| width | int | La larghezza della pagina. |
| height | int | L'altezza della pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, il nome, la visibilità, la larghezza, l'altezza e le linee specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| nome | java.lang.String | Il nome della pagina. |
| visibile | boolean | Il flag di visibilità. |
| width | int | La larghezza della pagina. |
| height | int | L'altezza della pagina. |
| linee | java.util.List<com.groupdocs.viewer.results.Line> | Le linee contenute nella pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Crea un'implementazione dell'interfaccia [Page](../../com.groupdocs.viewer.results/page) che rappresenta una pagina con il numero, la visibilità, la larghezza, l'altezza e le linee specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero di pagina. |
| visibile | boolean | Il flag di visibilità. |
| width | int | La larghezza della pagina. |
| height | int | L'altezza della pagina. |
| linee | java.util.List<com.groupdocs.viewer.results.Line> | Le linee contenute nella pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Crea un'implementazione dell'interfaccia [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) con il tipo di file, le pagine e il flag di stampa consentita specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine. |
| printingAllowed | boolean | Il flag che indica se la stampa è consentita. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Crea un'implementazione dell'interfaccia [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) con il tipo di file, le pagine, i livelli e i layout specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine. |
| livelli | java.util.List<com.groupdocs.viewer.results.Layer> | L'elenco dei livelli. |
| layout | java.util.List<com.groupdocs.viewer.results.Layout> | L'elenco dei layout. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Crea un'implementazione dell'interfaccia [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) con il tipo di file, le pagine, la data di inizio e la data di fine specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo di file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine. |
| startDate | java.util.Date | La data di inizio. |
| endDate | java.util.Date | La data di fine. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Crea un'implementazione dell'interfaccia [TextElement](../../com.groupdocs.viewer.results/textelement) con il valore, le coordinate e le dimensioni specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore. |
| x | double | La coordinata X. |
| y | double | La coordinata Y. |
| width | double | La larghezza. |
| height | double | L'altezza. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Crea un'implementazione dell'interfaccia MboxViewInfo con il tipo di file, le pagine e il conteggio delle note specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Il tipo del file. |
| pagine | java.util.List<com.groupdocs.viewer.results.Page> | L'elenco delle pagine da visualizzare. |
| notesCount | int | Il conteggio delle note contenuto dal file di archiviazione del database Lotus. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - una nuova istanza dell'implementazione MboxViewInfo.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Crea un'implementazione dell'interfaccia [Word](../../com.groupdocs.viewer.results/word) con la parola, le coordinate, le dimensioni e i caratteri specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parola | java.lang.String | La parola. |
| x | double | La coordinata X del punto più alto a sinistra del layout della pagina dove inizia il rettangolo che contiene la parola. |
| y | double | La coordinata Y del punto più alto a sinistra del layout della pagina dove inizia il rettangolo che contiene la parola. |
| width | double | La larghezza del rettangolo che contiene la parola (in pixel). |
| height | double | L'altezza del rettangolo che contiene la parola (in pixel). |
| caratteri | java.util.List<com.groupdocs.viewer.results.Character> | I caratteri contenuti nella parola. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
