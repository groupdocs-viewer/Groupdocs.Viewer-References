---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "此类帮助自定义。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

此类帮助自定义 [Cache](../../com.groupdocs.viewer.caching/cache)。

可以通过在此类中重写方法来实现自定义序列化模型，以返回自定义模型而不是嵌入的模型。为实现此目的，扩展 CacheableFactory 并激活它，将自定义工厂的新实例传递给 [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) 方法。

示例用法：

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

有关自定义缓存的更多细节、指南和示例，请参阅 [GroupDocs.Viewer documentation][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | 获取一个 CacheableFactory 实例，可用于创建可缓存对象。 |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | 设置要使用的 CacheableFactory 实例。 |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | 为指定的文件类型和页面创建 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 接口的实现。 |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 为指定的文件类型、页面和笔记计数创建 [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) 接口的实现。 |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 为指定的文件类型、页面和文件夹创建 [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) 接口的实现。 |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | 为指定的字符、位置和尺寸创建 [Character](../../com.groupdocs.viewer.results/character) 接口的实现。 |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | 为指定的文件类型创建 [FileInfo](../../com.groupdocs.viewer.results/fileinfo) 接口的实现。 |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | 使用指定的名称和可见性创建 [Layer](../../com.groupdocs.viewer.results/layer) 接口的实现。 |
| [newLayer(String name)](#newLayer-java.lang.String-) | 使用指定的名称创建 [Layer](../../com.groupdocs.viewer.results/layer) 接口的实现。 |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | 使用指定的名称、宽度和高度创建 [Layout](../../com.groupdocs.viewer.results/layout) 接口的实现。 |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | 使用指定的行、位置、尺寸和单词创建 [Line](../../com.groupdocs.viewer.results/line) 接口的实现。 |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | 创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。 |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | 创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。 |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | 创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。 |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | 创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。 |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 基于指定的文件类型、页面列表和文件夹列表创建 [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) 接口的实现。 |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | 创建表示具有指定编号和可见性的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。 |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | 创建表示具有指定编号、名称和可见性的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。 |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | 创建表示具有指定编号、名称、可见性、宽度和高度的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。 |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | 创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、可见性、宽度和高度的页面。 |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、名称、可见性、宽度、高度和行的页面。 |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、可见性、宽度、高度和行的页面。 |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | 创建一个 [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) 接口的实现，具有指定的文件类型、页面和允许打印的标志。 |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | 创建一个 [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) 接口的实现，具有指定的文件类型、页面、图层和布局。 |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | 创建一个 [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) 接口的实现，具有指定的文件类型、页面、开始日期和结束日期。 |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | 创建一个 [TextElement](../../com.groupdocs.viewer.results/textelement) 接口的实现，具有指定的值、坐标和尺寸。 |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 创建一个 MboxViewInfo 接口的实现，具有指定的文件类型、页面和注释计数。 |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | 创建一个 [Word](../../com.groupdocs.viewer.results/word) 接口的实现，具有指定的单词、坐标、尺寸和字符。 |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


获取一个 CacheableFactory 实例，可用于创建可缓存对象。

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


设置要使用的 CacheableFactory 实例。这允许对可缓存工厂进行自定义实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | 要设置的 CacheableFactory 实例。 |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


为指定的文件类型和页面创建 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 表示文档页面的页面列表。 |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


为指定的文件类型、页面和笔记计数创建 [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 表示文档页面的页面列表。 |
| notesCount | int | 文档中 Lotus Notes 的计数。 |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


为指定的文件类型、页面和文件夹创建 [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 表示文档页面的页面列表。 |
| 文件夹 | java.util.List<java.lang.String> | 存档中的文件夹列表。 |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


为指定的字符、位置和尺寸创建 [Character](../../com.groupdocs.viewer.results/character) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字符 | char | 该字符。 |
| x | double | 字符位置的 x 坐标。 |
| y | double | 字符位置的 y 坐标。 |
| width | double | 字符的宽度。 |
| height | double | 字符的高度。 |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


为指定的文件类型创建 [FileInfo](../../com.groupdocs.viewer.results/fileinfo) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


使用指定的名称和可见性创建 [Layer](../../com.groupdocs.viewer.results/layer) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 图层的名称。 |
| 可见 | boolean | 图层的可见性。 |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


使用指定的名称创建 [Layer](../../com.groupdocs.viewer.results/layer) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 图层的名称。 |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


使用指定的名称、宽度和高度创建 [Layout](../../com.groupdocs.viewer.results/layout) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 布局的名称。 |
| width | double | 布局的宽度。 |
| height | double | 布局的高度。 |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


使用指定的行、位置、尺寸和单词创建 [Line](../../com.groupdocs.viewer.results/line) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | java.lang.String | 行内容。 |
| x | double | 包含该行的矩形左上角点的 X 坐标。 |
| y | double | 包含该行的矩形左上角点的 Y 坐标。 |
| width | double | 包含该行的矩形的宽度（像素）。 |
| height | double | 包含该行的矩形的高度（像素）。 |
| 单词 | java.util.List<com.groupdocs.viewer.results.Word> | 行中包含的单词。 |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 附件的名称。 |
| filePath | java.lang.String | 附件的相对路径，例如 "folder/file.docx"。当文件位于归档的根目录、电子邮件中或数据文件中时，请指定文件名。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ID | java.lang.String | 附件的 ID。 |
| fileName | java.lang.String | 附件的名称。 |
| filePath | java.lang.String | 附件的相对路径，例如 "folder/file.docx"。当文件位于归档的根目录、电子邮件中或数据文件中时，请指定文件名。 |
| 大小 | long | 附件的大小。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ID | java.lang.String | 附件的 ID。 |
| fileName | java.lang.String | 附件的名称。 |
| filePath | java.nio.file.Path | 附件的相对或绝对路径。 |
| 大小 | long | 附件的大小。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


创建 [Attachment](../../com.groupdocs.viewer.results/attachment) 接口的实现。该附件表示附加到文档或电子邮件的文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ID | java.lang.String | 附件的 ID。 |
| fileName | java.lang.String | 附件的名称。 |
| filePath | java.lang.String | 附件的相对或绝对路径。它可以是文件夹中的文件路径，或者如果文件位于归档根目录、电子邮件或数据文件中，则直接使用文件名。 |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 附件文件的类型。 |
| 大小 | long | 附件的大小。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


基于指定的文件类型、页面列表和文件夹列表创建 [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) 接口的实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 页面列表。 |
| 文件夹 | java.util.List<java.lang.String> | 文件夹列表。 |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


创建表示具有指定编号和可见性的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 可见 | boolean | 可见性标志。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


创建表示具有指定编号、名称和可见性的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 名称 | java.lang.String | 页面名称。 |
| 可见 | boolean | 可见性标志。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


创建表示具有指定编号、名称、可见性、宽度和高度的页面的 [Page](../../com.groupdocs.viewer.results/page) 接口实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 名称 | java.lang.String | 页面名称。 |
| 可见 | boolean | 可见性标志。 |
| width | int | 页面的宽度。 |
| height | int | 页面的高度。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、可见性、宽度和高度的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 可见 | boolean | 可见性标志。 |
| width | int | 页面的宽度。 |
| height | int | 页面的高度。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、名称、可见性、宽度、高度和行的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 名称 | java.lang.String | 页面名称。 |
| 可见 | boolean | 可见性标志。 |
| width | int | 页面的宽度。 |
| height | int | 页面的高度。 |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | 页面中包含的行。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


创建一个 [Page](../../com.groupdocs.viewer.results/page) 接口的实现，表示具有指定编号、可见性、宽度、高度和行的页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 页面编号。 |
| 可见 | boolean | 可见性标志。 |
| width | int | 页面的宽度。 |
| height | int | 页面的高度。 |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | 页面中包含的行。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


创建一个 [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) 接口的实现，具有指定的文件类型、页面和允许打印的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 页面列表。 |
| printingAllowed | boolean | 指示是否允许打印的标志。 |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


创建一个 [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) 接口的实现，具有指定的文件类型、页面、图层和布局。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 页面列表。 |
| 图层 | java.util.List<com.groupdocs.viewer.results.Layer> | 图层列表。 |
| 布局 | java.util.List<com.groupdocs.viewer.results.Layout> | 布局列表。 |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


创建一个 [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) 接口的实现，具有指定的文件类型、页面、开始日期和结束日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 页面列表。 |
| startDate | java.util.Date | 开始日期。 |
| endDate | java.util.Date | 结束日期。 |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


创建一个 [TextElement](../../com.groupdocs.viewer.results/textelement) 接口的实现，具有指定的值、坐标和尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | T | 该值。 |
| x | double | X 坐标。 |
| y | double | Y 坐标。 |
| width | double | 宽度。 |
| height | double | 高度。 |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


创建一个 MboxViewInfo 接口的实现，具有指定的文件类型、页面和注释计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 文件类型。 |
| 页面 | java.util.List<com.groupdocs.viewer.results.Page> | 要查看的页面列表。 |
| notesCount | int | Lotus 数据库存储文件中包含的笔记计数。 |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo 实现的新实例。
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


创建一个 [Word](../../com.groupdocs.viewer.results/word) 接口的实现，具有指定的单词、坐标、尺寸和字符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 单词 | java.lang.String | 该单词。 |
| x | double | 包含单词的矩形在页面布局中左上角的 X 坐标。 |
| y | double | 包含单词的矩形在页面布局中左上角的 Y 坐标。 |
| width | double | 包含单词的矩形的宽度（像素）。 |
| height | double | 包含单词的矩形的高度（像素）。 |
| 字符 | java.util.List<com.groupdocs.viewer.results.Character> | 单词包含的字符。 |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
