---
title: "CacheableFactory"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Этот класс помогает настраивать ."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Этот класс помогает настраивать [Cache](../../com.groupdocs.viewer.caching/cache).


Пользовательские модели для сериализации могут быть реализованы переопределением методов в этом классе, чтобы возвращать их вместо встроенных.
Для этого расширьте CacheableFactory и активируйте его, передав новый экземпляр пользовательской фабрики в метод [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-).


Пример использования:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


Для получения более подробной информации, рекомендаций и примеров по настройке кэша, пожалуйста, обратитесь к
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getInstance()](#getInstance--) | Получает экземпляр |
CacheableFactory
который может использоваться для создания кэшируемых объектов.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Устанавливает экземпляр |
CacheableFactory
для использования.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Создаёт реализацию интерфейса [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) для указанного типа файла и страниц. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Создаёт реализацию интерфейса [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) для указанного типа файла, страниц и количества заметок. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Создаёт реализацию интерфейса [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) для указанного типа файла, страниц и папок. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Создаёт реализацию интерфейса [Character](../../com.groupdocs.viewer.results/character) для указанного символа, позиции и размеров. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Создаёт реализацию интерфейса [FileInfo](../../com.groupdocs.viewer.results/fileinfo) для указанного типа файла. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Создает реализацию интерфейса [Layer](../../com.groupdocs.viewer.results/layer) с указанным именем и видимостью. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Создает реализацию интерфейса [Layer](../../com.groupdocs.viewer.results/layer) с указанным именем. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Создает реализацию интерфейса [Layout](../../com.groupdocs.viewer.results/layout) с указанным именем, шириной и высотой. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Создает реализацию интерфейса [Line](../../com.groupdocs.viewer.results/line) с указанной линией, позицией, размерами и словами. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Создает реализацию интерфейса [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) на основе указанного типа файла, |
список страниц и список папок.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером и видимостью. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем и видимостью. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем, видимостью, шириной и высотой. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, видимостью, шириной и высотой. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем, видимостью, шириной, высотой и линиями. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, видимостью, шириной, высотой и линиями. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Создает реализацию интерфейса [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) с указанным типом файла, страницами и флагом разрешения печати. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Создает реализацию интерфейса [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) с указанным типом файла, страницами, слоями и макетами. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Создает реализацию интерфейса [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) с указанным типом файла, страницами, датой начала и датой окончания. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Создает реализацию интерфейса [TextElement](../../com.groupdocs.viewer.results/textelement) с указанным значением, координатами и размерами. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Создает реализацию интерфейса MboxViewInfo с указанным типом файла, страницами и количеством заметок. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Создает реализацию интерфейса [Word](../../com.groupdocs.viewer.results/word) с указанным словом, координатами, размерами и символами. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Получает экземпляр
CacheableFactory
который может использоваться для создания кэшируемых объектов.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Устанавливает экземпляр
CacheableFactory
для использования. Это позволяет создать пользовательскую реализацию кэшируемой фабрики.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Экземпляр  CacheableFactory  для установки. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Создаёт реализацию интерфейса [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) для указанного типа файла и страниц.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц, представляющих страницы документа. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| страницы | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| тема | java.lang.String |  |
| от | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Создаёт реализацию интерфейса [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) для указанного типа файла, страниц и количества заметок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц, представляющих страницы документа. |
|
|  | Количество заметок | int | Количество Lotus Notes в документе. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Создаёт реализацию интерфейса [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) для указанного типа файла, страниц и папок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц, представляющих страницы документа. |
|
|  | папки | java.util.List<java.lang.String> | Список папок в архиве. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Создаёт реализацию интерфейса [Character](../../com.groupdocs.viewer.results/character) для указанного символа, позиции и размеров.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | символ | символ | Символ. |
|
|  | x | double | Координата x позиции символа. |
|
|  | y | double | Координата y позиции символа. |
|
|  | width | double | Ширина символа. |
|
|  | height | double | Высота символа. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Создаёт реализацию интерфейса [FileInfo](../../com.groupdocs.viewer.results/fileinfo) для указанного типа файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Создает реализацию интерфейса [Layer](../../com.groupdocs.viewer.results/layer) с указанным именем и видимостью.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя | java.lang.String | Имя слоя. |
|
|  | видимый | boolean | Видимость слоя. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Создает реализацию интерфейса [Layer](../../com.groupdocs.viewer.results/layer) с указанным именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя | java.lang.String | Имя слоя. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Создает реализацию интерфейса [Layout](../../com.groupdocs.viewer.results/layout) с указанным именем, шириной и высотой.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя | java.lang.String | Имя макета. |
|
|  | width | double | Ширина макета. |
|
|  | height | double | Высота макета. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Создает реализацию интерфейса [Line](../../com.groupdocs.viewer.results/line) с указанной линией, позицией, размерами и словами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | строка | java.lang.String | Содержимое строки. |
|
|  | x | double | Координата X верхнего левого угла прямоугольника, содержащего строку. |
|
|  | y | double | Координата Y верхнего левого угла прямоугольника, содержащего строку. |
|
|  | width | double | Ширина прямоугольника, содержащего строку (в пикселях). |
|
|  | height | double | Высота прямоугольника, содержащего строку (в пикселях). |
|
|  | слова | java.util.List<com.groupdocs.viewer.results.Word> | Слова, содержащиеся в строке. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Имя вложения. |
|
|  | filePath | java.lang.String | Относительный путь к вложению, например, "folder/file.docx". Когда файл находится в корне архива, в электронном письме или в файле данных, указывайте имя файла. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | id | java.lang.String | Идентификатор вложения. |
|
|  | fileName | java.lang.String | Имя вложения. |
|
|  | filePath | java.lang.String | Относительный путь к вложению, например, "folder/file.docx". Когда файл находится в корне архива, в электронном письме или в файле данных, указывайте имя файла. |
|
|  | size | long | Размер вложения. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Создает реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | id | java.lang.String | Идентификатор вложения. |
|
|  | fileName | java.lang.String | Имя вложения. |
|
|  | filePath | java.nio.file.Path | Относительный или абсолютный путь к вложению. |
|
|  | size | long | Размер вложения. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Создаёт реализацию интерфейса [Attachment](../../com.groupdocs.viewer.results/attachment). Вложение представляет файл, прикреплённый к документу или электронному письму.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | id | java.lang.String | Идентификатор вложения. |
|
|  | fileName | java.lang.String | Имя вложения. |
|
|  | filePath | java.lang.String | Относительный или абсолютный путь к вложению. Это может быть путь к файлу внутри папки или само имя файла, если файл находится в корне архива, в электронном письме или в файле данных. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла вложения. |
|
|  | size | long | Размер вложения. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Создает реализацию интерфейса [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) на основе указанного типа файла,
список страниц и список папок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц. |
|
|  | папки | java.util.List<java.lang.String> | Список папок. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером и видимостью.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем и видимостью.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | имя | java.lang.String | Имя страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем, видимостью, шириной и высотой.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | имя | java.lang.String | Имя страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|
|  | width | int | Ширина страницы. |
|
|  | height | int | Высота страницы. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, видимостью, шириной и высотой.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|
|  | width | int | Ширина страницы. |
|
|  | height | int | Высота страницы. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, именем, видимостью, шириной, высотой и линиями.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | имя | java.lang.String | Имя страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|
|  | width | int | Ширина страницы. |
|
|  | height | int | Высота страницы. |
|
|  | строки | java.util.List<com.groupdocs.viewer.results.Line> | Строки, содержащиеся на странице. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Создает реализацию интерфейса [Page](../../com.groupdocs.viewer.results/page), представляющего страницу с указанным номером, видимостью, шириной, высотой и линиями.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | number | int | Номер страницы. |
|
|  | видимый | boolean | Флаг видимости. |
|
|  | width | int | Ширина страницы. |
|
|  | height | int | Высота страницы. |
|
|  | строки | java.util.List<com.groupdocs.viewer.results.Line> | Строки, содержащиеся на странице. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Создает реализацию интерфейса [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) с указанным типом файла, страницами и флагом разрешения печати.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц. |
|
|  | printingAllowed | boolean | Флаг, указывающий, разрешена ли печать. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Создает реализацию интерфейса [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) с указанным типом файла, страницами, слоями и макетами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц. |
|
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | Список слоёв. |
|
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | Список макетов. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Создает реализацию интерфейса [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) с указанным типом файла, страницами, датой начала и датой окончания.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц. |
|
|  | startDate | java.util.Date | Дата начала. |
|
|  | endDate | java.util.Date | Дата окончания. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Создает реализацию интерфейса [TextElement](../../com.groupdocs.viewer.results/textelement) с указанным значением, координатами и размерами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | T | Значение. |
|
|  | x | double | Координата X. |
|
|  | y | double | Координата Y. |
|
|  | width | double | Ширина. |
|
|  | height | double | Высота. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Создает реализацию интерфейса MboxViewInfo с указанным типом файла, страницами и количеством заметок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Тип файла. |
|
|  | страницы | java.util.List<com.groupdocs.viewer.results.Page> | Список страниц для просмотра. |
|
|  | Количество заметок | int | Количество заметок, содержащихся в файле хранилища базы данных Lotus. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo — новый экземпляр реализации MboxViewInfo.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Создает реализацию интерфейса [Word](../../com.groupdocs.viewer.results/word) с указанным словом, координатами, размерами и символами.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | word | java.lang.String | Слово. |
|
|  | x | double | Координата X самой верхней левой точки в макете страницы, где начинается прямоугольник, содержащий слово. |
|
|  | y | double | Координата Y самой верхней левой точки в макете страницы, где начинается прямоугольник, содержащий слово. |
|
|  | width | double | Ширина прямоугольника, содержащего слово (в пикселях). |
|
|  | height | double | Высота прямоугольника, содержащего слово (в пикселях). |
|
|  | символы | java.util.List<com.groupdocs.viewer.results.Character> | Символы, содержащиеся в слове. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

