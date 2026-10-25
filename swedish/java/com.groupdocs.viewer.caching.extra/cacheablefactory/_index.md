---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Denna klass hjälper till att anpassa ."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Denna klass hjälper till att anpassa [Cache](../../com.groupdocs.viewer.caching/cache).


Anpassade modeller för serialisering kan implementeras genom att åsidosätta metoder i denna klass för att returnera dem istället för de inbäddade.
För att uppnå detta, ärva CacheableFactory och aktivera den genom att skicka en ny instans av en anpassad fabrik till metoden [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-).


Exempel på användning:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


För mer detaljer, riktlinjer och exempel på anpassning av cachen, se
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getInstance()](#getInstance--) | Hämtar en instans av |
CacheableFactory
som kan användas för att skapa cachebara objekt.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Ställer in instansen av |
CacheableFactory
att använda.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Skapar en implementation av gränssnittet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) för den angivna filtypen och sidorna. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Skapar en implementation av gränssnittet [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) för den angivna filtypen, sidorna och antalet anteckningar. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Skapar en implementation av gränssnittet [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) för den angivna filtypen, sidorna och mapparna. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Skapar en implementation av gränssnittet [Character](../../com.groupdocs.viewer.results/character) för det angivna tecknet, positionen och dimensionerna. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Skapar en implementation av gränssnittet [FileInfo](../../com.groupdocs.viewer.results/fileinfo) för den angivna filtypen. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Skapar en implementation av gränssnittet [Layer](../../com.groupdocs.viewer.results/layer) med det angivna namnet och synligheten. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Skapar en implementation av gränssnittet [Layer](../../com.groupdocs.viewer.results/layer) med det angivna namnet. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Skapar en implementation av gränssnittet [Layout](../../com.groupdocs.viewer.results/layout) med det angivna namnet, bredden och höjden. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Skapar en implementation av gränssnittet [Line](../../com.groupdocs.viewer.results/line) med den angivna raden, positionen, dimensionerna och orden. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Skapar en implementation av gränssnittet [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) baserat på den angivna filtypen, |
lista över sidor och lista över mappar.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret och synligheten. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet och synligheten. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet, synligheten, bredden och höjden. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, synligheten, bredden och höjden. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet, synligheten, bredden, höjden och linjerna. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, synligheten, bredden, höjden och linjerna. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Skapar en implementation av gränssnittet [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) med den angivna filtypen, sidorna och flaggan för tillåten utskrift. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Skapar en implementation av gränssnittet [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) med den angivna filtypen, sidorna, lagren och layouterna. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Skapar en implementation av gränssnittet [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) med den angivna filtypen, sidorna, startdatumet och slutdatumet. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Skapar en implementation av gränssnittet [TextElement](../../com.groupdocs.viewer.results/textelement) med det angivna värdet, koordinaterna och dimensionerna. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Skapar en implementation av gränssnittet MboxViewInfo med den angivna filtypen, sidorna och antalet anteckningar. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Skapar en implementation av gränssnittet [Word](../../com.groupdocs.viewer.results/word) med det angivna ordet, koordinaterna, dimensionerna och tecknen. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Hämtar en instans av
CacheableFactory
som kan användas för att skapa cachebara objekt.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Ställer in instansen av
CacheableFactory
att användas. Detta möjliggör en anpassad implementation av den cachebara fabriken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Instansen av  CacheableFactory  att ange. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Skapar en implementation av gränssnittet [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) för den angivna filtypen och sidorna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan med sidor som representerar dokumentets sidor. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| sidor | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| ämne | java.lang.String |  |
| från | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Skapar en implementation av gränssnittet [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) för den angivna filtypen, sidorna och antalet anteckningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan med sidor som representerar dokumentets sidor. |
|
|  | notesCount | int | Antalet Lotus Notes i dokumentet. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Skapar en implementation av gränssnittet [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) för den angivna filtypen, sidorna och mapparna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan med sidor som representerar dokumentets sidor. |
|
|  | mappar | java.util.List<java.lang.String> | Listan över mappar i arkivet. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Skapar en implementation av gränssnittet [Character](../../com.groupdocs.viewer.results/character) för det angivna tecknet, positionen och dimensionerna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | tecken | char | Tecknet. |
|
|  | x | double | X-koordinaten för teckenpositionen. |
|
|  | y | double | Y-koordinaten för teckenpositionen. |
|
|  | width | double | Bredden på tecknet. |
|
|  | höjd | double | Höjden på tecknet. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Skapar en implementation av gränssnittet [FileInfo](../../com.groupdocs.viewer.results/fileinfo) för den angivna filtypen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Skapar en implementation av gränssnittet [Layer](../../com.groupdocs.viewer.results/layer) med det angivna namnet och synligheten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på lagret. |
|
|  | synlig | boolean | Synligheten för lagret. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Skapar en implementation av gränssnittet [Layer](../../com.groupdocs.viewer.results/layer) med det angivna namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på lagret. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Skapar en implementation av gränssnittet [Layout](../../com.groupdocs.viewer.results/layout) med det angivna namnet, bredden och höjden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på layouten. |
|
|  | width | double | Bredden på layouten. |
|
|  | höjd | double | Höjden på layouten. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Skapar en implementation av gränssnittet [Line](../../com.groupdocs.viewer.results/line) med den angivna raden, positionen, dimensionerna och orden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rad | java.lang.String | Radens innehåll. |
|
|  | x | double | X-koordinaten för det övre vänstra hörnet av rektangeln som innehåller raden. |
|
|  | y | double | Y-koordinaten för det övre vänstra hörnet av rektangeln som innehåller raden. |
|
|  | width | double | Bredden på rektangeln som innehåller raden (i pixlar). |
|
|  | höjd | double | Höjden på rektangeln som innehåller raden (i pixlar). |
|
|  | ord | java.util.List<com.groupdocs.viewer.results.Word> | Orden som finns i raden. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileName | java.lang.String | Namnet på bilagan. |
|
|  | filePath | java.lang.String | Den relativa sökvägen till bilagan, t.ex. "folder/file.docx". När filen finns i rotkatalogen för ett arkiv, i ett e‑postmeddelande eller i en datafil, ange filnamnet. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | java.lang.String | Bilagans ID. |
|
|  | fileName | java.lang.String | Namnet på bilagan. |
|
|  | filePath | java.lang.String | Den relativa sökvägen till bilagan, t.ex. "folder/file.docx". När filen finns i rotkatalogen för ett arkiv, i ett e‑postmeddelande eller i en datafil, ange filnamnet. |
|
|  | size | long | Bilagans storlek. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | java.lang.String | Bilagans ID. |
|
|  | fileName | java.lang.String | Namnet på bilagan. |
|
|  | filePath | java.nio.file.Path | Den relativa eller absoluta sökvägen till bilagan. |
|
|  | size | long | Bilagans storlek. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Skapar en implementation av gränssnittet [Attachment](../../com.groupdocs.viewer.results/attachment). Bilagan representerar en fil som är bifogad till ett dokument eller ett e‑postmeddelande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | java.lang.String | Bilagans ID. |
|
|  | fileName | java.lang.String | Namnet på bilagan. |
|
|  | filePath | java.lang.String | Den relativa eller absoluta sökvägen till bilagan. Det kan vara en filsökväg inom en mapp eller själva filnamnet om filen finns i rotkatalogen för ett arkiv, i ett e‑postmeddelande eller i en datafil. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Bilagans filtyp. |
|
|  | size | long | Bilagans storlek. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Skapar en implementation av gränssnittet [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) baserat på den angivna filtypen,
lista över sidor och lista över mappar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan över sidor. |
|
|  | mappar | java.util.List<java.lang.String> | Listan över mappar. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret och synligheten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | synlig | boolean | Synlighetsflagga. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet och synligheten.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | namn | java.lang.String | Sidnamn. |
|
|  | synlig | boolean | Synlighetsflagga. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet, synligheten, bredden och höjden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | namn | java.lang.String | Sidnamn. |
|
|  | synlig | boolean | Synlighetsflagga. |
|
|  | width | int | Sidans bredd. |
|
|  | höjd | int | Sidans höjd. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, synligheten, bredden och höjden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | synlig | boolean | Synlighetsflagga. |
|
|  | width | int | Sidans bredd. |
|
|  | höjd | int | Sidans höjd. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, namnet, synligheten, bredden, höjden och linjerna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | namn | java.lang.String | Sidnamn. |
|
|  | synlig | boolean | Synlighetsflagga. |
|
|  | width | int | Sidans bredd. |
|
|  | höjd | int | Sidans höjd. |
|
|  | rader | java.util.List<com.groupdocs.viewer.results.Line> | Raderna som finns på sidan. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Skapar en implementation av gränssnittet [Page](../../com.groupdocs.viewer.results/page) som representerar en sida med det angivna numret, synligheten, bredden, höjden och linjerna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nummer | int | Sidnummer. |
|
|  | synlig | boolean | Synlighetsflagga. |
|
|  | width | int | Sidans bredd. |
|
|  | höjd | int | Sidans höjd. |
|
|  | rader | java.util.List<com.groupdocs.viewer.results.Line> | Raderna som finns på sidan. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Skapar en implementation av gränssnittet [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) med den angivna filtypen, sidorna och flaggan för tillåten utskrift.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan över sidor. |
|
|  | printingAllowed | boolean | Flaggan som indikerar om utskrift är tillåten. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Skapar en implementation av gränssnittet [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) med den angivna filtypen, sidorna, lagren och layouterna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan över sidor. |
|
|  | lager | java.util.List<com.groupdocs.viewer.results.Layer> | Listan med lager. |
|
|  | layouter | java.util.List<com.groupdocs.viewer.results.Layout> | Listan med layouter. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Skapar en implementation av gränssnittet [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) med den angivna filtypen, sidorna, startdatumet och slutdatumet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filtypen. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan över sidor. |
|
|  | startDate | java.util.Date | Startdatumet. |
|
|  | endDate | java.util.Date | Slutdatumet. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Skapar en implementation av gränssnittet [TextElement](../../com.groupdocs.viewer.results/textelement) med det angivna värdet, koordinaterna och dimensionerna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | T | Värdet. |
|
|  | x | double | X-koordinaten. |
|
|  | y | double | Y-koordinaten. |
|
|  | width | double | Bredden. |
|
|  | höjd | double | Höjden. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Skapar en implementation av gränssnittet MboxViewInfo med den angivna filtypen, sidorna och antalet anteckningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Filens typ. |
|
|  | sidor | java.util.List<com.groupdocs.viewer.results.Page> | Listan med sidor att visa. |
|
|  | notesCount | int | Antalet anteckningar som finns i Lotus-databasens lagringsfil. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - en ny instans av MboxViewInfo-implementationen.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Skapar en implementation av gränssnittet [Word](../../com.groupdocs.viewer.results/word) med det angivna ordet, koordinaterna, dimensionerna och tecknen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ord | java.lang.String | Ordet. |
|
|  | x | double | X-koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller ordet börjar. |
|
|  | y | double | Y-koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller ordet börjar. |
|
|  | width | double | Bredden på rektangeln som innehåller ordet (i pixlar). |
|
|  | höjd | double | Höjden på rektangeln som innehåller ordet (i pixlar). |
|
|  | tecken | java.util.List<com.groupdocs.viewer.results.Character> | Tecknen som ordet innehåller. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

