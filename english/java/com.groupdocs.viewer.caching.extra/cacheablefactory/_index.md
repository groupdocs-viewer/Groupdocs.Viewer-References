---
title: CacheableFactory
second_title: GroupDocs.Viewer for Java API Reference
description: This class helps customize .
type: docs
weight: 10
url: /java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

This class helps customize [Cache](../../com.groupdocs.viewer.caching/cache).

Custom models for serialization can be implemented by overriding methods in this class to return them instead of the embedded ones. To achieve this, extend CacheableFactory and activate it passing new instance of custom factory to [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) method.

Example usage:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

For more details, guidelines, and examples on customizing the cache, please refer to the [GroupDocs.Viewer documentation][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Constructors

| Constructor | Description |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Gets an instance of  CacheableFactory  that can be used to create cacheable objects. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Sets the instance of  CacheableFactory  to be used. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Creates an implementation of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface for the specified file type and pages. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Creates an implementation of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface for the specified file type, pages, and notes count. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Creates an implementation of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) interface for the specified file type, pages, and folders. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Creates an implementation of the [Character](../../com.groupdocs.viewer.results/character) interface for the specified character, position, and dimensions. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Creates an implementation of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) interface for the specified file type. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Creates an implementation of the [Layer](../../com.groupdocs.viewer.results/layer) interface with the specified name and visibility. |
| [newLayer(String name)](#newLayer-java.lang.String-) | Creates an implementation of the [Layer](../../com.groupdocs.viewer.results/layer) interface with the specified name. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Creates an implementation of the [Layout](../../com.groupdocs.viewer.results/layout) interface with the specified name, width, and height. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Creates an implementation of the [Line](../../com.groupdocs.viewer.results/line) interface with the specified line, position, dimensions, and words. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface. |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Creates an implementation of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) interface based on the specified file type, list of pages, and list of folders. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number and visibility. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, and visibility. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, visibility, width, and height. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, visibility, width, and height. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, visibility, width, height, and lines. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, visibility, width, height, and lines. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Creates an implementation of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) interface with the specified file type, pages, and printing allowed flag. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Creates an implementation of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) interface with the specified file type, pages, layers, and layouts. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Creates an implementation of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) interface with the specified file type, pages, start date, and end date. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Creates an implementation of the [TextElement](../../com.groupdocs.viewer.results/textelement) interface with the specified value, coordinates, and dimensions. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Creates an implementation of the MboxViewInfo interface with the specified file type, pages, and notes count. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Creates an implementation of the [Word](../../com.groupdocs.viewer.results/word) interface with the specified word, coordinates, dimensions, and characters. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Gets an instance of  CacheableFactory  that can be used to create cacheable objects.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Sets the instance of  CacheableFactory  to be used. This allows custom implementation of the cacheable factory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | The instance of  CacheableFactory  to set. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Creates an implementation of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) interface for the specified file type and pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages representing the document pages. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Creates an implementation of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) interface for the specified file type, pages, and notes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages representing the document pages. |
| notesCount | int | The count of Lotus Notes in the document. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Creates an implementation of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) interface for the specified file type, pages, and folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages representing the document pages. |
| folders | java.util.List<java.lang.String> | The list of folders in the archive. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Creates an implementation of the [Character](../../com.groupdocs.viewer.results/character) interface for the specified character, position, and dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | The character. |
| x | double | The x-coordinate of the character position. |
| y | double | The y-coordinate of the character position. |
| width | double | The width of the character. |
| height | double | The height of the character. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Creates an implementation of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) interface for the specified file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Creates an implementation of the [Layer](../../com.groupdocs.viewer.results/layer) interface with the specified name and visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the layer. |
| visible | boolean | The visibility of the layer. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Creates an implementation of the [Layer](../../com.groupdocs.viewer.results/layer) interface with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the layer. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Creates an implementation of the [Layout](../../com.groupdocs.viewer.results/layout) interface with the specified name, width, and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the layout. |
| width | double | The width of the layout. |
| height | double | The height of the layout. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Creates an implementation of the [Line](../../com.groupdocs.viewer.results/line) interface with the specified line, position, dimensions, and words.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | java.lang.String | The line content. |
| x | double | The X coordinate of the top-left point of the rectangle that contains the line. |
| y | double | The Y coordinate of the top-left point of the rectangle that contains the line. |
| width | double | The width of the rectangle that contains the line (in pixels). |
| height | double | The height of the rectangle that contains the line (in pixels). |
| words | java.util.List<com.groupdocs.viewer.results.Word> | The words contained in the line. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The name of the attachment. |
| filePath | java.lang.String | The relative path of the attachment, e.g., "folder/file.docx". When the file is located in the root of an archive, in an email message, or a data file, specify the filename. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The ID of the attachment. |
| fileName | java.lang.String | The name of the attachment. |
| filePath | java.lang.String | The relative path of the attachment, e.g., "folder/file.docx". When the file is located in the root of an archive, in an email message, or a data file, specify the filename. |
| size | long | The size of the attachment. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The ID of the attachment. |
| fileName | java.lang.String | The name of the attachment. |
| filePath | java.nio.file.Path | The relative or absolute path of the attachment. |
| size | long | The size of the attachment. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Creates an implementation of the [Attachment](../../com.groupdocs.viewer.results/attachment) interface. The attachment represents a file attached to a document or an email message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | The ID of the attachment. |
| fileName | java.lang.String | The name of the attachment. |
| filePath | java.lang.String | The relative or absolute path of the attachment. It can be a file path within a folder or the filename itself if the file is located in the root of an archive, in an email message, or in a data file. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The type of the attachment file. |
| size | long | The size of the attachment. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Creates an implementation of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) interface based on the specified file type, list of pages, and list of folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages. |
| folders | java.util.List<java.lang.String> | The list of folders. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number and visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| visible | boolean | The visibility flag. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, and visibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| name | java.lang.String | The page name. |
| visible | boolean | The visibility flag. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, visibility, width, and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| name | java.lang.String | The page name. |
| visible | boolean | The visibility flag. |
| width | int | The width of the page. |
| height | int | The height of the page. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, visibility, width, and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| visible | boolean | The visibility flag. |
| width | int | The width of the page. |
| height | int | The height of the page. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, name, visibility, width, height, and lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| name | java.lang.String | The page name. |
| visible | boolean | The visibility flag. |
| width | int | The width of the page. |
| height | int | The height of the page. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | The lines contained in the page. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Creates an implementation of the [Page](../../com.groupdocs.viewer.results/page) interface representing a page with the specified number, visibility, width, height, and lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| visible | boolean | The visibility flag. |
| width | int | The width of the page. |
| height | int | The height of the page. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | The lines contained in the page. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Creates an implementation of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) interface with the specified file type, pages, and printing allowed flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages. |
| printingAllowed | boolean | The flag indicating whether printing is allowed. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Creates an implementation of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) interface with the specified file type, pages, layers, and layouts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages. |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | The list of layers. |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | The list of layouts. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Creates an implementation of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) interface with the specified file type, pages, start date, and end date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages. |
| startDate | java.util.Date | The start date. |
| endDate | java.util.Date | The end date. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Creates an implementation of the [TextElement](../../com.groupdocs.viewer.results/textelement) interface with the specified value, coordinates, and dimensions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value. |
| x | double | The X coordinate. |
| y | double | The Y coordinate. |
| width | double | The width. |
| height | double | The height. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Creates an implementation of the MboxViewInfo interface with the specified file type, pages, and notes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The type of the file. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages to view. |
| notesCount | int | The notes count contained by the Lotus database storage file. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - a new instance of the MboxViewInfo implementation.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Creates an implementation of the [Word](../../com.groupdocs.viewer.results/word) interface with the specified word, coordinates, dimensions, and characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| word | java.lang.String | The word. |
| x | double | The X coordinate of the highest left point on the page layout where the rectangle that contains the word begins. |
| y | double | The Y coordinate of the highest left point on the page layout where the rectangle that contains the word begins. |
| width | double | The width of the rectangle which contains the word (in pixels). |
| height | double | The height of the rectangle which contains the word (in pixels). |
| characters | java.util.List<com.groupdocs.viewer.results.Character> | The characters contained by the word. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
