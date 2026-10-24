---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "هذه الفئة تساعد في تخصيص ."
type: docs
weight: 10
url: /ar/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

هذه الفئة تساعد في تخصيص [Cache](../../com.groupdocs.viewer.caching/cache).


يمكن تنفيذ نماذج مخصصة للتسلسل عبر تجاوز الأساليب في هذه الفئة لإرجاعها بدلاً من النماذج المدمجة.
لتحقيق ذلك، قم بتمديد CacheableFactory وتفعيله بتمرير نسخة جديدة من المصنع المخصص إلى طريقة [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-).


مثال على الاستخدام:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


لمزيد من التفاصيل والإرشادات والأمثلة حول تخصيص الذاكرة المؤقتة، يرجى الرجوع إلى
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getInstance()](#getInstance--) | يحصل على نسخة من |
CacheableFactory
التي يمكن استخدامها لإنشاء كائنات قابلة للتخزين المؤقت.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | يضبط نسخة من |
CacheableFactory
لاستخدامها.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | ينشئ تنفيذًا لواجهة [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) للنوع المحدد من الملف والصفحات. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | ينشئ تنفيذًا لواجهة [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) للنوع المحدد من الملف، الصفحات، وعدد الملاحظات. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | ينشئ تنفيذًا لواجهة [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) للنوع المحدد من الملف، الصفحات، والمجلدات. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | ينشئ تنفيذًا لواجهة [Character](../../com.groupdocs.viewer.results/character) للحرف المحدد، الموقع، والأبعاد. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | ينشئ تنفيذًا لواجهة [FileInfo](../../com.groupdocs.viewer.results/fileinfo) للنوع المحدد من الملف. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | ينشئ تنفيذًا لواجهة [Layer](../../com.groupdocs.viewer.results/layer) بالاسم المحدد والظهور. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | ينشئ تنفيذًا لواجهة [Layer](../../com.groupdocs.viewer.results/layer) بالاسم المحدد. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | ينشئ تنفيذًا لواجهة [Layout](../../com.groupdocs.viewer.results/layout) بالاسم والعرض والارتفاع المحددين. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | ينشئ تنفيذًا لواجهة [Line](../../com.groupdocs.viewer.results/line) بالخط المحدد، الموضع، الأبعاد، والكلمات. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | ينشئ تنفيذًا لواجهة [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) بناءً على نوع الملف المحدد، |
قائمة الصفحات، وقائمة المجلدات.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور المحددين. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور المحددين. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور والعرض والارتفاع المحددين. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور والعرض والارتفاع المحددين. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور والعرض والارتفاع والأسطر المحددة. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور والعرض والارتفاع والأسطر المحددة. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | ينشئ تنفيذًا لواجهة [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) بنوع الملف والصفحات وعلامة السماح بالطباعة المحددة. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | ينشئ تنفيذًا لواجهة [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) بنوع الملف والصفحات والطبقات والتصاميم المحددة. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | ينشئ تنفيذًا لواجهة [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) بنوع الملف والصفحات وتاريخ البدء وتاريخ الانتهاء المحددين. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | ينشئ تنفيذًا لواجهة [TextElement](../../com.groupdocs.viewer.results/textelement) بالقيمة والإحداثيات والأبعاد المحددة. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | ينشئ تنفيذًا لواجهة MboxViewInfo بنوع الملف والصفحات وعدد الملاحظات المحدد. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | ينشئ تنفيذًا لواجهة [Word](../../com.groupdocs.viewer.results/word) بالكلمة والإحداثيات والأبعاد والحروف المحددة. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


يحصل على نسخة من
CacheableFactory
التي يمكن استخدامها لإنشاء كائنات قابلة للتخزين المؤقت.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


يضبط نسخة من
CacheableFactory
يُستخدم. يتيح هذا تنفيذًا مخصصًا للمصنع القابل للتخزين المؤقت.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | مثيل CacheableFactory لتعيينه. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


ينشئ تنفيذًا لواجهة [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) للنوع المحدد من الملف والصفحات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات التي تمثل صفحات المستند. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| صفحات | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| الموضوع | java.lang.String |  |
| من | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


ينشئ تنفيذًا لواجهة [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) للنوع المحدد من الملف، الصفحات، وعدد الملاحظات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات التي تمثل صفحات المستند. |
|
|  | notesCount | int | عدد ملاحظات Lotus في المستند. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


ينشئ تنفيذًا لواجهة [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) للنوع المحدد من الملف، الصفحات، والمجلدات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات التي تمثل صفحات المستند. |
|
|  | المجلدات | java.util.List<java.lang.String> | قائمة المجلدات في الأرشيف. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


ينشئ تنفيذًا لواجهة [Character](../../com.groupdocs.viewer.results/character) للحرف المحدد، الموقع، والأبعاد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الحرف | char | الحرف. |
|
|  | x | double | الإحداثي السيني لموضع الحرف. |
|
|  | y | double | الإحداثي الصادي لموضع الحرف. |
|
|  | width | double | عرض الحرف. |
|
|  | ارتفاع | double | ارتفاع الحرف. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


ينشئ تنفيذًا لواجهة [FileInfo](../../com.groupdocs.viewer.results/fileinfo) للنوع المحدد من الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


ينشئ تنفيذًا لواجهة [Layer](../../com.groupdocs.viewer.results/layer) بالاسم المحدد والظهور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | name | java.lang.String | اسم الطبقة. |
|
|  | مرئي | boolean | رؤية الطبقة. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


ينشئ تنفيذًا لواجهة [Layer](../../com.groupdocs.viewer.results/layer) بالاسم المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | name | java.lang.String | اسم الطبقة. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


ينشئ تنفيذًا لواجهة [Layout](../../com.groupdocs.viewer.results/layout) بالاسم والعرض والارتفاع المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | name | java.lang.String | اسم التخطيط. |
|
|  | width | double | عرض التخطيط. |
|
|  | ارتفاع | double | ارتفاع التخطيط. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


ينشئ تنفيذًا لواجهة [Line](../../com.groupdocs.viewer.results/line) بالخط المحدد، الموضع، الأبعاد، والكلمات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | السطر | java.lang.String | محتوى السطر. |
|
|  | x | double | الإحداثي السيني للنقطة العلوية اليسرى للمستطيل الذي يحتوي على السطر. |
|
|  | y | double | الإحداثي الصادي للنقطة العلوية اليسرى للمستطيل الذي يحتوي على السطر. |
|
|  | width | double | عرض المستطيل الذي يحتوي على السطر (بالبكسل). |
|
|  | ارتفاع | double | ارتفاع المستطيل الذي يحتوي على السطر (بالبكسل). |
|
|  | كلمات | java.util.List<com.groupdocs.viewer.results.Word> | الكلمات الموجودة في السطر. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileName | java.lang.String | اسم المرفق. |
|
|  | filePath | java.lang.String | المسار النسبي للمرفق، على سبيل المثال "folder/file.docx". عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو في ملف بيانات، حدد اسم الملف. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | id | java.lang.String | معرّف المرفق. |
|
|  | fileName | java.lang.String | اسم المرفق. |
|
|  | filePath | java.lang.String | المسار النسبي للمرفق، على سبيل المثال "folder/file.docx". عندما يكون الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو في ملف بيانات، حدد اسم الملف. |
|
|  | size | long | حجم المرفق. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | id | java.lang.String | معرّف المرفق. |
|
|  | fileName | java.lang.String | اسم المرفق. |
|
|  | filePath | java.nio.file.Path | المسار النسبي أو المطلق للمرفق. |
|
|  | size | long | حجم المرفق. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


ينشئ تنفيذًا لواجهة [Attachment](../../com.groupdocs.viewer.results/attachment). يمثل المرفق ملفًا مرفقًا بوثيقة أو رسالة بريد إلكتروني.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | id | java.lang.String | معرّف المرفق. |
|
|  | fileName | java.lang.String | اسم المرفق. |
|
|  | filePath | java.lang.String | المسار النسبي أو المطلق للمرفق. يمكن أن يكون مسار ملف داخل مجلد أو اسم الملف نفسه إذا كان الملف موجودًا في جذر الأرشيف أو في رسالة بريد إلكتروني أو في ملف بيانات. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع ملف المرفق. |
|
|  | size | long | حجم المرفق. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


ينشئ تنفيذًا لواجهة [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) بناءً على نوع الملف المحدد،
قائمة الصفحات، وقائمة المجلدات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات. |
|
|  | المجلدات | java.util.List<java.lang.String> | قائمة المجلدات. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | name | java.lang.String | اسم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور والعرض والارتفاع المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | name | java.lang.String | اسم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|
|  | width | int | عرض الصفحة. |
|
|  | ارتفاع | int | ارتفاع الصفحة. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور والعرض والارتفاع المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|
|  | width | int | عرض الصفحة. |
|
|  | ارتفاع | int | ارتفاع الصفحة. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والاسم والظهور والعرض والارتفاع والأسطر المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | name | java.lang.String | اسم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|
|  | width | int | عرض الصفحة. |
|
|  | ارتفاع | int | ارتفاع الصفحة. |
|
|  | سطور | java.util.List<com.groupdocs.viewer.results.Line> | السطور الموجودة في الصفحة. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


ينشئ تنفيذًا لواجهة [Page](../../com.groupdocs.viewer.results/page) تمثّل صفحة بالرقم والظهور والعرض والارتفاع والأسطر المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | رقم الصفحة. |
|
|  | مرئي | boolean | علامة الظهور. |
|
|  | width | int | عرض الصفحة. |
|
|  | ارتفاع | int | ارتفاع الصفحة. |
|
|  | سطور | java.util.List<com.groupdocs.viewer.results.Line> | السطور الموجودة في الصفحة. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


ينشئ تنفيذًا لواجهة [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) بنوع الملف والصفحات وعلامة السماح بالطباعة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات. |
|
|  | printingAllowed | boolean | العلم الذي يشير إلى ما إذا كان الطباعة مسموحة. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


ينشئ تنفيذًا لواجهة [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) بنوع الملف والصفحات والطبقات والتصاميم المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات. |
|
|  | الطبقات | java.util.List<com.groupdocs.viewer.results.Layer> | قائمة الطبقات. |
|
|  | التخطيطات | java.util.List<com.groupdocs.viewer.results.Layout> | قائمة التخطيطات. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


ينشئ تنفيذًا لواجهة [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) بنوع الملف والصفحات وتاريخ البدء وتاريخ الانتهاء المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات. |
|
|  | startDate | java.util.Date | تاريخ البدء. |
|
|  | endDate | java.util.Date | تاريخ الانتهاء. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


ينشئ تنفيذًا لواجهة [TextElement](../../com.groupdocs.viewer.results/textelement) بالقيمة والإحداثيات والأبعاد المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | T | القيمة. |
|
|  | x | double | الإحداثي X. |
|
|  | y | double | الإحداثي Y. |
|
|  | width | double | العرض. |
|
|  | ارتفاع | double | الارتفاع. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


ينشئ تنفيذًا لواجهة MboxViewInfo بنوع الملف والصفحات وعدد الملاحظات المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|
|  | صفحات | java.util.List<com.groupdocs.viewer.results.Page> | قائمة الصفحات للعرض. |
|
|  | notesCount | int | عدد الملاحظات الموجود في ملف تخزين قاعدة بيانات Lotus. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - نسخة جديدة من تنفيذ MboxViewInfo.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


ينشئ تنفيذًا لواجهة [Word](../../com.groupdocs.viewer.results/word) بالكلمة والإحداثيات والأبعاد والحروف المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة | java.lang.String | الكلمة. |
|
|  | x | double | إحداثي X لأعلى نقطة على اليسار في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي الكلمة. |
|
|  | y | double | إحداثي Y لأعلى نقطة على اليسار في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي الكلمة. |
|
|  | width | double | عرض المستطيل الذي يحتوي الكلمة (بالبكسل). |
|
|  | ارتفاع | double | ارتفاع المستطيل الذي يحتوي الكلمة (بالبكسل). |
|
|  | الأحرف | java.util.List<com.groupdocs.viewer.results.Character> | الأحرف التي يحتويها الكلمة. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

