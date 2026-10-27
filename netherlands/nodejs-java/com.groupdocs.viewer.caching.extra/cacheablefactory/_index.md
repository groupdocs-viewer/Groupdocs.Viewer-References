---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Deze klasse helpt bij het aanpassen."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Deze klasse helpt bij het aanpassen van [Cache](../../com.groupdocs.viewer.caching/cache).

Aangepaste modellen voor serialisatie kunnen worden geïmplementeerd door methoden in deze klasse te overschrijven zodat ze deze in plaats van de ingebedde teruggeven. Om dit te bereiken, breidt u CacheableFactory uit en activeert u deze door een nieuw exemplaar van de aangepaste fabriek door te geven aan de [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) methode.

Voorbeeldgebruik:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

Voor meer details, richtlijnen en voorbeelden over het aanpassen van de cache, raadpleeg de [GroupDocs.Viewer-documentatie][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | Haalt een instantie van  CacheableFactory  op die kan worden gebruikt om cachebare objecten te maken. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Stelt de instantie van  CacheableFactory  in die moet worden gebruikt. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Maakt een implementatie van de [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface voor het opgegeven bestandstype en de pagina's. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Maakt een implementatie van de [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface voor het opgegeven bestandstype, de pagina's en het aantal notities. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Maakt een implementatie van de [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) interface voor het opgegeven bestandstype, de pagina's en de mappen. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Maakt een implementatie van de [Character](../../com.groupdocs.viewer.results/character) interface voor het opgegeven teken, de positie en de afmetingen. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Maakt een implementatie van de [FileInfo](../../com.groupdocs.viewer.results/fileinfo) interface voor het opgegeven bestandstype. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Maakt een implementatie van de [Layer](../../com.groupdocs.viewer.results/layer) interface met de opgegeven naam en zichtbaarheid. |
| [newLayer(String name)](#newLayer-java.lang.String-) | Maakt een implementatie van de [Layer](../../com.groupdocs.viewer.results/layer) interface met de opgegeven naam. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Maakt een implementatie van de [Layout](../../com.groupdocs.viewer.results/layout) interface met de opgegeven naam, breedte en hoogte. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Maakt een implementatie van de [Line](../../com.groupdocs.viewer.results/line) interface met de opgegeven regel, positie, afmetingen en woorden. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Maakt een implementatie van de [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) interface op basis van het opgegeven bestandstype, de lijst met pagina's en de lijst met mappen. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer en de zichtbaarheid. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam en zichtbaarheid. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam, zichtbaarheid, breedte en hoogte. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, zichtbaarheid, breedte en hoogte. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam, zichtbaarheid, breedte, hoogte en regels. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, zichtbaarheid, breedte, hoogte en regels. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Maakt een implementatie van de [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) interface met het opgegeven bestandstype, pagina's en afdrukken toegestaan vlag. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Maakt een implementatie van de [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) interface met het opgegeven bestandstype, pagina's, lagen en lay-outs. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Maakt een implementatie van de [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) interface met het opgegeven bestandstype, pagina's, startdatum en einddatum. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Maakt een implementatie van de [TextElement](../../com.groupdocs.viewer.results/textelement) interface met de opgegeven waarde, coördinaten en afmetingen. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Maakt een implementatie van de MboxViewInfo interface met het opgegeven bestandstype, pagina's en aantal notities. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Maakt een implementatie van de [Word](../../com.groupdocs.viewer.results/word) interface met het opgegeven woord, coördinaten, afmetingen en tekens. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Haalt een instantie van  CacheableFactory  op die kan worden gebruikt om cachebare objecten te maken.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Stelt de instantie van  CacheableFactory  in die gebruikt moet worden. Dit maakt een aangepaste implementatie van de cachebare fabriek mogelijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | De instantie van  CacheableFactory  die moet worden ingesteld. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Maakt een implementatie van de [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface voor het opgegeven bestandstype en de pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's die de documentpagina's vertegenwoordigen. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Maakt een implementatie van de [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface voor het opgegeven bestandstype, de pagina's en het aantal notities.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's die de documentpagina's vertegenwoordigen. |
| notesCount | int | Het aantal Lotus Notes in het document. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Maakt een implementatie van de [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) interface voor het opgegeven bestandstype, de pagina's en de mappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's die de documentpagina's vertegenwoordigen. |
| mappen | java.util.List<java.lang.String> | De lijst met mappen in het archief. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Maakt een implementatie van de [Character](../../com.groupdocs.viewer.results/character) interface voor het opgegeven teken, de positie en de afmetingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| teken | char | Het teken. |
| x | double | De x-coördinaat van de tekenpositie. |
| y | double | De y-coördinaat van de tekenpositie. |
| width | double | De breedte van het teken. |
| height | double | De hoogte van het teken. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Maakt een implementatie van de [FileInfo](../../com.groupdocs.viewer.results/fileinfo) interface voor het opgegeven bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Maakt een implementatie van de [Layer](../../com.groupdocs.viewer.results/layer) interface met de opgegeven naam en zichtbaarheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de laag. |
| zichtbaar | boolean | De zichtbaarheid van de laag. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Maakt een implementatie van de [Layer](../../com.groupdocs.viewer.results/layer) interface met de opgegeven naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de laag. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Maakt een implementatie van de [Layout](../../com.groupdocs.viewer.results/layout) interface met de opgegeven naam, breedte en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de lay-out. |
| width | double | De breedte van de lay-out. |
| height | double | De hoogte van de lay-out. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Maakt een implementatie van de [Line](../../com.groupdocs.viewer.results/line) interface met de opgegeven regel, positie, afmetingen en woorden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regel | java.lang.String | De inhoud van de regel. |
| x | double | De X-coördinaat van het linkerbovenpunt van de rechthoek die de regel bevat. |
| y | double | De Y-coördinaat van het linkerbovenpunt van de rechthoek die de regel bevat. |
| width | double | De breedte van de rechthoek die de regel bevat (in pixels). |
| height | double | De hoogte van de rechthoek die de regel bevat (in pixels). |
| woorden | java.util.List<com.groupdocs.viewer.results.Word> | De woorden die in de regel staan. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De naam van de bijlage. |
| filePath | java.lang.String | Het relatieve pad van de bijlage, bijv. "folder/file.docx". Wanneer het bestand zich bevindt in de root van een archief, in een e‑mailbericht, of een gegevensbestand, geef dan de bestandsnaam op. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | De ID van de bijlage. |
| fileName | java.lang.String | De naam van de bijlage. |
| filePath | java.lang.String | Het relatieve pad van de bijlage, bijv. "folder/file.docx". Wanneer het bestand zich bevindt in de root van een archief, in een e‑mailbericht, of een gegevensbestand, geef dan de bestandsnaam op. |
| grootte | long | De grootte van de bijlage. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | De ID van de bijlage. |
| fileName | java.lang.String | De naam van de bijlage. |
| filePath | java.nio.file.Path | Het relatieve of absolute pad van de bijlage. |
| grootte | long | De grootte van de bijlage. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Maakt een implementatie van de [Attachment](../../com.groupdocs.viewer.results/attachment) interface. De attachment vertegenwoordigt een bestand dat is bijgevoegd aan een document of een e‑mailbericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | De ID van de bijlage. |
| fileName | java.lang.String | De naam van de bijlage. |
| filePath | java.lang.String | Het relatieve of absolute pad van de attachment. Het kan een bestandspad binnen een map zijn of de bestandsnaam zelf als het bestand zich bevindt in de root van een archief, in een e‑mailbericht, of in een gegevensbestand. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het type van het attachment‑bestand. |
| grootte | long | De grootte van de bijlage. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Maakt een implementatie van de [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) interface op basis van het opgegeven bestandstype, de lijst met pagina's en de lijst met mappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's. |
| mappen | java.util.List<java.lang.String> | De lijst met mappen. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer en de zichtbaarheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam en zichtbaarheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| naam | java.lang.String | De paginanaam. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam, zichtbaarheid, breedte en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| naam | java.lang.String | De paginanaam. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |
| width | int | De breedte van de pagina. |
| height | int | De hoogte van de pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, zichtbaarheid, breedte en hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |
| width | int | De breedte van de pagina. |
| height | int | De hoogte van de pagina. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, naam, zichtbaarheid, breedte, hoogte en regels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| naam | java.lang.String | De paginanaam. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |
| width | int | De breedte van de pagina. |
| height | int | De hoogte van de pagina. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | De regels die in de pagina zijn opgenomen. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Maakt een implementatie van de [Page](../../com.groupdocs.viewer.results/page) interface die een pagina vertegenwoordigt met het opgegeven nummer, zichtbaarheid, breedte, hoogte en regels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| zichtbaar | boolean | De zichtbaarheidsvlag. |
| width | int | De breedte van de pagina. |
| height | int | De hoogte van de pagina. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | De regels die in de pagina zijn opgenomen. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Maakt een implementatie van de [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) interface met het opgegeven bestandstype, pagina's en afdrukken toegestaan vlag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's. |
| printingAllowed | boolean | De vlag die aangeeft of afdrukken is toegestaan. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Maakt een implementatie van de [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) interface met het opgegeven bestandstype, pagina's, lagen en lay-outs.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's. |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | De lijst met lagen. |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | De lijst met lay-outs. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Maakt een implementatie van de [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) interface met het opgegeven bestandstype, pagina's, startdatum en einddatum.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het bestandstype. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's. |
| startDate | java.util.Date | De startdatum. |
| endDate | java.util.Date | De einddatum. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Maakt een implementatie van de [TextElement](../../com.groupdocs.viewer.results/textelement) interface met de opgegeven waarde, coördinaten en afmetingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde. |
| x | double | De X-coördinaat. |
| y | double | De Y-coördinaat. |
| width | double | De breedte. |
| height | double | De hoogte. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Maakt een implementatie van de MboxViewInfo interface met het opgegeven bestandstype, pagina's en aantal notities.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Het type van het bestand. |
| pagina's | java.util.List<com.groupdocs.viewer.results.Page> | De lijst met pagina's om te bekijken. |
| notesCount | int | Het aantal notities dat in het Lotus-databaseopslagbestand zit. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - een nieuw exemplaar van de MboxViewInfo-implementatie.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Maakt een implementatie van de [Word](../../com.groupdocs.viewer.results/word) interface met het opgegeven woord, coördinaten, afmetingen en tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| woord | java.lang.String | Het woord. |
| x | double | De X-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die het woord bevat begint. |
| y | double | De Y-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die het woord bevat begint. |
| width | double | De breedte van de rechthoek die het woord bevat (in pixels). |
| height | double | De hoogte van de rechthoek die het woord bevat (in pixels). |
| tekens | java.util.List<com.groupdocs.viewer.results.Character> | De tekens die in het woord zitten. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
