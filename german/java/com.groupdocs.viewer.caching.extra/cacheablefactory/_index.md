---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Diese Klasse hilft beim Anpassen ."
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Diese Klasse hilft beim Anpassen des [Cache](../../com.groupdocs.viewer.caching/cache).


Benutzerdefinierte Modelle für die Serialisierung können implementiert werden, indem Methoden in dieser Klasse überschrieben werden, um sie anstelle der eingebetteten zurückzugeben.
Um dies zu erreichen, erweitern Sie CacheableFactory und aktivieren Sie sie, indem Sie eine neue Instanz der benutzerdefinierten Fabrik an die Methode [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-) übergeben.


Beispielverwendung:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


Für weitere Details, Richtlinien und Beispiele zum Anpassen des Caches, bitte beachten Sie die
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getInstance()](#getInstance--) | Erhält eine Instanz von |
CacheableFactory
die verwendet werden kann, um cachefähige Objekte zu erstellen.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Setzt die Instanz von |
CacheableFactory
die verwendet werden soll.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Erstellt eine Implementierung des [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Interface für den angegebenen Dateityp und die Seiten. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Erstellt eine Implementierung des [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo)-Interface für den angegebenen Dateityp, die Seiten und die Anzahl der Notizen. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Erstellt eine Implementierung des [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo)-Interface für den angegebenen Dateityp, die Seiten und Ordner. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Erstellt eine Implementierung des [Character](../../com.groupdocs.viewer.results/character)-Interface für das angegebene Zeichen, die Position und die Abmessungen. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Erstellt eine Implementierung des [FileInfo](../../com.groupdocs.viewer.results/fileinfo)-Interface für den angegebenen Dateityp. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Erstellt eine Implementierung des [Layer](../../com.groupdocs.viewer.results/layer)-Interface mit dem angegebenen Namen und der Sichtbarkeit. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Erstellt eine Implementierung des [Layer](../../com.groupdocs.viewer.results/layer)-Interface mit dem angegebenen Namen. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Erstellt eine Implementierung des [Layout](../../com.groupdocs.viewer.results/layout)-Interface mit dem angegebenen Namen, der Breite und der Höhe. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Erstellt eine Implementierung des [Line](../../com.groupdocs.viewer.results/line)-Interface mit der angegebenen Zeile, Position, den Abmessungen und den Wörtern. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface. |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface. |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface. |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface. |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Erstellt eine Implementierung des [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo)-Interface basierend auf dem angegebenen Dateityp, |
Liste der Seiten und Liste der Ordner.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer und Sichtbarkeit darstellt. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen und der Sichtbarkeit darstellt. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen, der Sichtbarkeit, Breite und Höhe darstellt. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, der Sichtbarkeit, Breite und Höhe darstellt. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen, der Sichtbarkeit, Breite, Höhe und Zeilen darstellt. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, der Sichtbarkeit, Breite, Höhe und Zeilen darstellt. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Erstellt eine Implementierung der [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten und dem Druck‑erlaubt‑Flag. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Erstellt eine Implementierung der [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten, Ebenen und Layouts. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Erstellt eine Implementierung der [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten, dem Startdatum und dem Enddatum. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Erstellt eine Implementierung der [TextElement](../../com.groupdocs.viewer.results/textelement)-Schnittstelle mit dem angegebenen Wert, den Koordinaten und den Abmessungen. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Erstellt eine Implementierung der MboxViewInfo‑Schnittstelle mit dem angegebenen Dateityp, den Seiten und der Notizanzahl. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Erstellt eine Implementierung der [Word](../../com.groupdocs.viewer.results/word)-Schnittstelle mit dem angegebenen Wort, den Koordinaten, den Abmessungen und den Zeichen. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Erhält eine Instanz von
CacheableFactory
die verwendet werden kann, um cachefähige Objekte zu erstellen.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Setzt die Instanz von
CacheableFactory
Zu verwenden. Dies ermöglicht eine benutzerdefinierte Implementierung der cachefähigen Fabrik.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Die Instanz von  CacheableFactory  zum Setzen. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Erstellt eine Implementierung des [ViewInfo](../../com.groupdocs.viewer.results/viewinfo)-Interface für den angegebenen Dateityp und die Seiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten, die die Dokumentseiten darstellen. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| Seiten | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| Betreff | java.lang.String |  |
| Von | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Erstellt eine Implementierung des [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo)-Interface für den angegebenen Dateityp, die Seiten und die Anzahl der Notizen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten, die die Dokumentseiten darstellen. |
|
|  | notesCount | int | Die Anzahl der Lotus‑Notes im Dokument. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Erstellt eine Implementierung des [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo)-Interface für den angegebenen Dateityp, die Seiten und Ordner.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten, die die Dokumentseiten darstellen. |
|
|  | Ordner | java.util.List<java.lang.String> | Die Liste der Ordner im Archiv. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Erstellt eine Implementierung des [Character](../../com.groupdocs.viewer.results/character)-Interface für das angegebene Zeichen, die Position und die Abmessungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeichen | char | Das Zeichen. |
|
|  | x | double | Die x-Koordinate der Zeichenposition. |
|
|  | y | double | Die y-Koordinate der Zeichenposition. |
|
|  | width | double | Die Breite des Zeichens. |
|
|  | height | double | Die Höhe des Zeichens. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Erstellt eine Implementierung des [FileInfo](../../com.groupdocs.viewer.results/fileinfo)-Interface für den angegebenen Dateityp.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Erstellt eine Implementierung des [Layer](../../com.groupdocs.viewer.results/layer)-Interface mit dem angegebenen Namen und der Sichtbarkeit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der Name der Ebene. |
|
|  | sichtbar | boolesch | Die Sichtbarkeit der Ebene. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Erstellt eine Implementierung des [Layer](../../com.groupdocs.viewer.results/layer)-Interface mit dem angegebenen Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der Name der Ebene. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Erstellt eine Implementierung des [Layout](../../com.groupdocs.viewer.results/layout)-Interface mit dem angegebenen Namen, der Breite und der Höhe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der Name des Layouts. |
|
|  | width | double | Die Breite des Layouts. |
|
|  | height | double | Die Höhe des Layouts. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Erstellt eine Implementierung des [Line](../../com.groupdocs.viewer.results/line)-Interface mit der angegebenen Zeile, Position, den Abmessungen und den Wörtern.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeile | java.lang.String | Der Zeileninhalt. |
|
|  | x | double | Die X-Koordinate des oberen linken Punktes des Rechtecks, das die Zeile enthält. |
|
|  | y | double | Die Y-Koordinate des oberen linken Punktes des Rechtecks, das die Zeile enthält. |
|
|  | width | double | Die Breite des Rechtecks, das die Zeile enthält (in Pixeln). |
|
|  | height | double | Die Höhe des Rechtecks, das die Zeile enthält (in Pixeln). |
|
|  | Wörter | java.util.List<com.groupdocs.viewer.results.Word> | Die in der Zeile enthaltenen Wörter. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Der Name des Anhangs. |
|
|  | filePath | java.lang.String | Der relative Pfad des Anhangs, z. B. "folder/file.docx". Wenn die Datei im Stamm eines Archivs, in einer E‑Mail‑Nachricht oder in einer Datendatei liegt, geben Sie den Dateinamen an. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | id | java.lang.String | Die ID des Anhangs. |
|
|  | fileName | java.lang.String | Der Name des Anhangs. |
|
|  | filePath | java.lang.String | Der relative Pfad des Anhangs, z. B. "folder/file.docx". Wenn die Datei im Stamm eines Archivs, in einer E‑Mail‑Nachricht oder in einer Datendatei liegt, geben Sie den Dateinamen an. |
|
|  | size | long | Die Größe des Anhangs. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Erstellt eine Implementierung des [Attachment](../../com.groupdocs.viewer.results/attachment)-Interface.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | id | java.lang.String | Die ID des Anhangs. |
|
|  | fileName | java.lang.String | Der Name des Anhangs. |
|
|  | filePath | java.nio.file.Path | Der relative oder absolute Pfad des Anhangs. |
|
|  | size | long | Die Größe des Anhangs. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Erstellt eine Implementierung der [Attachment](../../com.groupdocs.viewer.results/attachment)-Schnittstelle. Der Anhang stellt eine an ein Dokument oder eine E‑Mail‑Nachricht angehängte Datei dar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | id | java.lang.String | Die ID des Anhangs. |
|
|  | fileName | java.lang.String | Der Name des Anhangs. |
|
|  | filePath | java.lang.String | Der relative oder absolute Pfad des Anhangs. Er kann ein Dateipfad innerhalb eines Ordners oder der Dateiname selbst sein, wenn die Datei im Stamm eines Archivs, in einer E‑Mail‑Nachricht oder in einer Datendatei liegt. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Typ der Anhangsdatei. |
|
|  | size | long | Die Größe des Anhangs. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Erstellt eine Implementierung des [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo)-Interface basierend auf dem angegebenen Dateityp,
Liste der Seiten und Liste der Ordner.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten. |
|
|  | Ordner | java.util.List<java.lang.String> | Die Liste der Ordner. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer und Sichtbarkeit darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen und der Sichtbarkeit darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | Name | java.lang.String | Der Seitenname. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen, der Sichtbarkeit, Breite und Höhe darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | Name | java.lang.String | Der Seitenname. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|
|  | width | int | Die Breite der Seite. |
|
|  | height | int | Die Höhe der Seite. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, der Sichtbarkeit, Breite und Höhe darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|
|  | width | int | Die Breite der Seite. |
|
|  | height | int | Die Höhe der Seite. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, dem Namen, der Sichtbarkeit, Breite, Höhe und Zeilen darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | Name | java.lang.String | Der Seitenname. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|
|  | width | int | Die Breite der Seite. |
|
|  | height | int | Die Höhe der Seite. |
|
|  | lines | java.util.List<com.groupdocs.viewer.results.Line> | Die Zeilen, die in der Seite enthalten sind. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Erstellt eine Implementierung der [Page](../../com.groupdocs.viewer.results/page)-Schnittstelle, die eine Seite mit der angegebenen Nummer, der Sichtbarkeit, Breite, Höhe und Zeilen darstellt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die Seitennummer. |
|
|  | sichtbar | boolesch | Das Sichtbarkeits‑Flag. |
|
|  | width | int | Die Breite der Seite. |
|
|  | height | int | Die Höhe der Seite. |
|
|  | lines | java.util.List<com.groupdocs.viewer.results.Line> | Die Zeilen, die in der Seite enthalten sind. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Erstellt eine Implementierung der [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten und dem Druck‑erlaubt‑Flag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten. |
|
|  | printingAllowed | boolesch | Das Flag, das angibt, ob das Drucken erlaubt ist. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Erstellt eine Implementierung der [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten, Ebenen und Layouts.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten. |
|
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | Die Liste der Ebenen. |
|
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | Die Liste der Layouts. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Erstellt eine Implementierung der [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo)-Schnittstelle mit dem angegebenen Dateityp, den Seiten, dem Startdatum und dem Enddatum.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Dateityp. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der Seiten. |
|
|  | startDate | java.util.Date | Das Startdatum. |
|
|  | endDate | java.util.Date | Das Enddatum. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Erstellt eine Implementierung der [TextElement](../../com.groupdocs.viewer.results/textelement)-Schnittstelle mit dem angegebenen Wert, den Koordinaten und den Abmessungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | T | Der Wert. |
|
|  | x | double | Die X-Koordinate. |
|
|  | y | double | Die Y-Koordinate. |
|
|  | width | double | Die Breite. |
|
|  | height | double | Die Höhe. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Erstellt eine Implementierung der MboxViewInfo‑Schnittstelle mit dem angegebenen Dateityp, den Seiten und der Notizanzahl.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Der Typ der Datei. |
|
|  | Seiten | java.util.List<com.groupdocs.viewer.results.Page> | Die Liste der anzuzeigenden Seiten. |
|
|  | notesCount | int | Die Notizanzahl, die in der Lotus-Datenbankspeicherdatei enthalten ist. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo – eine neue Instanz der MboxViewInfo-Implementierung.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Erstellt eine Implementierung der [Word](../../com.groupdocs.viewer.results/word)-Schnittstelle mit dem angegebenen Wort, den Koordinaten, den Abmessungen und den Zeichen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | word | java.lang.String | Das Wort. |
|
|  | x | double | Die X-Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
|
|  | y | double | Die Y-Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
|
|  | width | double | Die Breite des Rechtecks, das das Wort enthält (in Pixeln). |
|
|  | height | double | Die Höhe des Rechtecks, das das Wort enthält (in Pixeln). |
|
|  | characters | java.util.List<com.groupdocs.viewer.results.Character> | Die Zeichen, die im Wort enthalten sind. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

