---
title: CacheableFactory
second_title: GroupDocs.Viewer for Java API Reference
description: This class helps customising . You can implement your custom models for serialization and override methods in this class for return them instead of embedded ones. Just extend CacheableFactory and call .setInstancenew YourCustomCacheableFactory More details in documentation
type: docs
weight: 10
url: /java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

This class helps customising [Cache](../../com.groupdocs.viewer.caching/cache).
You can implement your custom models for serialization and override methods in this class for return them instead of embedded ones.
Just extend CacheableFactory and call [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory).setInstance(new YourCustomCacheableFactory())
More details in [documentation][]


[documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Constructors

| Constructor | Description |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Gets instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Sets instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Creates implementation of [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Creates implementation of [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Creates implementation of ArchiveViewInfo interface |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Creates implementation of LotusNotesViewInfo interface |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Creates implementation of LotusNotesViewInfo interface |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Creates implementation of LotusNotesViewInfo interface |
| [newLayer(String name)](#newLayer-java.lang.String-) | Creates implementation of LotusNotesViewInfo interface |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Creates implementation of LotusNotesViewInfo interface |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Creates implementation of Line interface |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Creates implementation of LotusNotesViewInfo interface |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Creates implementation of LotusNotesViewInfo interface |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Creates implementation of LotusNotesViewInfo interface |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Creates implementation of LotusNotesViewInfo interface |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Creates implementation of LotusNotesViewInfo interface |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Creates implementation of LotusNotesViewInfo interface |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Creates implementation of LotusNotesViewInfo interface |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Creates implementation of LotusNotesViewInfo interface |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Creates implementation of TextElement interface |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Creates implementation of TextElement interface |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Creates implementation of LotusNotesViewInfo interface |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Gets instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory)

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory)
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Sets instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | instance of [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Creates implementation of [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - new instance of [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Creates implementation of [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| notesCount | int | nodes count |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - new instance of [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Creates implementation of ArchiveViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| folders | java.util.List<java.lang.String> | folders |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - new instance of [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | character |
| x | double | x |
| y | double | y |
| width | double | width |
| height | double | height |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - new instance of [Character](../../com.groupdocs.viewer.results/character) implementation
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - new instance of [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name |
| visible | boolean | visibility |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - new instance of [Layer](../../com.groupdocs.viewer.results/layer) implementation
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - new instance of [Layer](../../com.groupdocs.viewer.results/layer) implementation
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name |
| width | double | width |
| height | double | height |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - new instance of [Layout](../../com.groupdocs.viewer.results/layout) implementation
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Creates implementation of Line interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The line. |
| x | double | The X coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| y | double | The Y coordinate of the highest left point on the page layout where the rectangle that contains line begins. |
| width | double | The width of the rectangle which contains the line (in pixels). |
| height | double | The height of the rectangle which contains the line (in pixels). |
| words | java.util.List<com.groupdocs.viewer.results.Word> | The words contained by the line. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line)
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | file name |
| filePath | java.lang.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - new instance of [Attachment](../../com.groupdocs.viewer.results/attachment) implementation
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | id |
| fileName | java.lang.String | file name |
| filePath | java.lang.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| size | long | size |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - new instance of [Attachment](../../com.groupdocs.viewer.results/attachment) implementation
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | id |
| fileName | java.lang.String | file name |
| filePath | java.lang.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| size | long | size |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - new instance of [Attachment](../../com.groupdocs.viewer.results/attachment) implementation
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| folders | java.util.List<java.lang.String> | folders |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - new instance of [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| visible | boolean | visibility |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| name | java.lang.String | name |
| visible | boolean | visibility |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| name | java.lang.String | name |
| visible | boolean | visibility |
| width | int | width |
| height | int | height |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| visible | boolean | visibility |
| width | int | width |
| height | int | height |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| name | java.lang.String | name |
| visible | boolean | visibility |
| width | int | width |
| height | int | height |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | lines |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | number |
| visible | boolean | visibility |
| width | int | width |
| height | int | height |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | lines |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - new instance of [Page](../../com.groupdocs.viewer.results/page) implementation
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| printingAllowed | boolean | printing allowed |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - new instance of [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | layers |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | layouts |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - new instance of [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | file type |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | pages |
| startDate | java.util.Date | start date |
| endDate | java.util.Date | end date |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - new instance of [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Creates implementation of TextElement interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | T | the value |
| x | double | x |
| y | double | y |
| width | double | width |
| height | double | height |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - new instance of [TextElement](../../com.groupdocs.viewer.results/textelement) implementation
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Creates implementation of TextElement interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The type of the file. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages to view. |
| notesCount | int | The notes count contained by the Lotus database storage file. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - new instance of MboxViewInfo implementation
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Creates implementation of LotusNotesViewInfo interface

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| word | java.lang.String | the word |
| x | double | x |
| y | double | y |
| width | double | width |
| height | double | height |
| characters | java.util.List<com.groupdocs.viewer.results.Character> | characters |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - new instance of [Word](../../com.groupdocs.viewer.results/word) implementation
