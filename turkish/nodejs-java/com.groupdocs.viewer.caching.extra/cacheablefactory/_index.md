---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bu sınıf özelleştirmeye yardımcı olur."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Bu sınıf [Cache](../../com.groupdocs.viewer.caching/cache) özelleştirmeye yardımcı olur.

Serileştirme için özel modeller, bu sınıftaki yöntemleri geçersiz kılarak gömülü olanlar yerine döndürülerek uygulanabilir. Bunu başarmak için CacheableFactory'yi genişletin ve özel fabrikanın yeni örneğini [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) yöntemine geçirerek etkinleştirin.

Örnek kullanım:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

Önbelleği özelleştirme hakkında daha fazla ayrıntı, kılavuz ve örnekler için lütfen [GroupDocs.Viewer belgeleri][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInstance()](#getInstance--) | CacheableFactory'nin önbelleklenebilir nesneler oluşturmak için kullanılabilecek bir örneğini alır. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Kullanılacak CacheableFactory örneğini ayarlar. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Belirtilen dosya türü ve sayfalar için [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Belirtilen dosya türü, sayfalar ve not sayısı için [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Belirtilen dosya türü, sayfalar ve klasörler için [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Belirtilen karakter, konum ve boyutlar için [Character](../../com.groupdocs.viewer.results/character) arayüzünün bir uygulamasını oluşturur. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Belirtilen dosya türü için [FileInfo](../../com.groupdocs.viewer.results/fileinfo) arayüzünün bir uygulamasını oluşturur. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Belirtilen ad ve görünürlük ile [Layer](../../com.groupdocs.viewer.results/layer) arayüzünün bir uygulamasını oluşturur. |
| [newLayer(String name)](#newLayer-java.lang.String-) | Belirtilen ad ile [Layer](../../com.groupdocs.viewer.results/layer) arayüzünün bir uygulamasını oluşturur. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Belirtilen ad, genişlik ve yükseklik ile [Layout](../../com.groupdocs.viewer.results/layout) arayüzünün bir uygulamasını oluşturur. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Belirtilen satır, konum, boyutlar ve kelimeler ile [Line](../../com.groupdocs.viewer.results/line) arayüzünün bir uygulamasını oluşturur. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | [Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur. |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur. |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur. |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur. |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Belirtilen dosya türü, sayfa listesi ve klasör listesine göre [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Belirtilen numara ve görünürlük ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Belirtilen numara, ad ve görünürlük ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Belirtilen numara, ad, görünürlük, genişlik ve yükseklik ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Belirtilen numara, görünürlük, genişlik ve yükseklikte bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Belirtilen numara, ad, görünürlük, genişlik, yükseklik ve satırlarla bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Belirtilen numara, görünürlük, genişlik, yükseklik ve satırlarla bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Belirtilen dosya türü, sayfalar ve yazdırma izin bayrağı ile [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Belirtilen dosya türü, sayfalar, katmanlar ve düzenlerle [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Belirtilen dosya türü, sayfalar, başlangıç tarihi ve bitiş tarihi ile [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) arayüzünün bir uygulamasını oluşturur. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Belirtilen değer, koordinatlar ve boyutlarla [TextElement](../../com.groupdocs.viewer.results/textelement) arayüzünün bir uygulamasını oluşturur. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Belirtilen dosya türü, sayfalar ve not sayısı ile MboxViewInfo arayüzünün bir uygulamasını oluşturur. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Belirtilen kelime, koordinatlar, boyutlar ve karakterlerle [Word](../../com.groupdocs.viewer.results/word) arayüzünün bir uygulamasını oluşturur. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


CacheableFactory'nin önbelleklenebilir nesneler oluşturmak için kullanılabilecek bir örneğini alır.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Kullanılacak CacheableFactory örneğini ayarlar. Bu, önbelleklenebilir fabrikanın özel bir uygulamasına izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Ayarlanacak CacheableFactory örneği. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Belirtilen dosya türü ve sayfalar için [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Belge sayfalarını temsil eden sayfalar listesidir. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Belirtilen dosya türü, sayfalar ve not sayısı için [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Belge sayfalarını temsil eden sayfalar listesidir. |
| notesCount | int | Belgedeki Lotus Notes sayısı. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Belirtilen dosya türü, sayfalar ve klasörler için [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Belge sayfalarını temsil eden sayfalar listesidir. |
| klasörler | java.util.List<java.lang.String> | Arşivdeki klasörlerin listesi. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Belirtilen karakter, konum ve boyutlar için [Character](../../com.groupdocs.viewer.results/character) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| karakter | char | Karakter. |
| x | double | Karakter konumunun x-koordinatı. |
| y | double | Karakter konumunun y-koordinatı. |
| width | double | Karakterin genişliği. |
| height | double | Karakterin yüksekliği. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Belirtilen dosya türü için [FileInfo](../../com.groupdocs.viewer.results/fileinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Belirtilen ad ve görünürlük ile [Layer](../../com.groupdocs.viewer.results/layer) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Katmanın adı. |
| görünür | boolean | Katmanın görünürlüğü. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Belirtilen ad ile [Layer](../../com.groupdocs.viewer.results/layer) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Katmanın adı. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Belirtilen ad, genişlik ve yükseklik ile [Layout](../../com.groupdocs.viewer.results/layout) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Düzenin adı. |
| width | double | Düzenin genişliği. |
| height | double | Düzenin yüksekliği. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Belirtilen satır, konum, boyutlar ve kelimeler ile [Line](../../com.groupdocs.viewer.results/line) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satır | java.lang.String | Satır içeriği. |
| x | double | Satırı içeren dikdörtgenin sol üst noktasının X koordinatı. |
| y | double | Satırı içeren dikdörtgenin sol üst noktasının Y koordinatı. |
| width | double | Satırı içeren dikdörtgenin genişliği (piksel cinsinden). |
| height | double | Satırı içeren dikdörtgenin yüksekliği (piksel cinsinden). |
| kelimeler | java.util.List<com.groupdocs.viewer.results.Word> | Satırda bulunan kelimeler. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Ek dosyanın adı. |
| filePath | java.lang.String | Ek dosyanın göreli yolu, ör. "folder/file.docx". Dosya bir arşivin kökünde, bir e-posta mesajında veya bir veri dosyasında bulunuyorsa, dosya adını belirtin. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Ek dosyanın kimliği. |
| fileName | java.lang.String | Ek dosyanın adı. |
| filePath | java.lang.String | Ek dosyanın göreli yolu, ör. "folder/file.docx". Dosya bir arşivin kökünde, bir e-posta mesajında veya bir veri dosyasında bulunuyorsa, dosya adını belirtin. |
| size | long | Ek dosyanın boyutu. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Ek dosyanın kimliği. |
| fileName | java.lang.String | Ek dosyanın adı. |
| filePath | java.nio.file.Path | Ek dosyanın göreli veya mutlak yolu. |
| size | long | Ek dosyanın boyutu. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Bir [Attachment](../../com.groupdocs.viewer.results/attachment) arabiriminin uygulanmasını oluşturur. Ek, bir belgeye veya e-posta mesajına eklenmiş bir dosyayı temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Ek dosyanın kimliği. |
| fileName | java.lang.String | Ek dosyanın adı. |
| filePath | java.lang.String | Ek'in göreceli veya mutlak yolu. Dosya, bir klasör içindeki dosya yolu olabileceği gibi, arşivin kökünde, bir e-posta mesajında veya bir veri dosyasında bulunuyorsa dosya adı da olabilir. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ek dosyasının türü. |
| size | long | Ek dosyanın boyutu. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Belirtilen dosya türü, sayfa listesi ve klasör listesine göre [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Sayfaların listesi. |
| klasörler | java.util.List<java.lang.String> | Klasörlerin listesi. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Belirtilen numara ve görünürlük ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| görünür | boolean | Görünürlük bayrağı. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Belirtilen numara, ad ve görünürlük ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| ad | java.lang.String | Sayfa adı. |
| görünür | boolean | Görünürlük bayrağı. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Belirtilen numara, ad, görünürlük, genişlik ve yükseklik ile bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| ad | java.lang.String | Sayfa adı. |
| görünür | boolean | Görünürlük bayrağı. |
| width | int | Sayfanın genişliği. |
| height | int | Sayfanın yüksekliği. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Belirtilen numara, görünürlük, genişlik ve yükseklikte bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| görünür | boolean | Görünürlük bayrağı. |
| width | int | Sayfanın genişliği. |
| height | int | Sayfanın yüksekliği. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Belirtilen numara, ad, görünürlük, genişlik, yükseklik ve satırlarla bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| ad | java.lang.String | Sayfa adı. |
| görünür | boolean | Görünürlük bayrağı. |
| width | int | Sayfanın genişliği. |
| height | int | Sayfanın yüksekliği. |
| satırlar | java.util.List<com.groupdocs.viewer.results.Line> | Sayfada bulunan satırlar. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Belirtilen numara, görünürlük, genişlik, yükseklik ve satırlarla bir sayfayı temsil eden [Page](../../com.groupdocs.viewer.results/page) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| görünür | boolean | Görünürlük bayrağı. |
| width | int | Sayfanın genişliği. |
| height | int | Sayfanın yüksekliği. |
| satırlar | java.util.List<com.groupdocs.viewer.results.Line> | Sayfada bulunan satırlar. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Belirtilen dosya türü, sayfalar ve yazdırma izin bayrağı ile [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Sayfaların listesi. |
| printingAllowed | boolean | Yazdırmanın izinli olup olmadığını gösteren bayrak. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Belirtilen dosya türü, sayfalar, katmanlar ve düzenlerle [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Sayfaların listesi. |
| katmanlar | java.util.List<com.groupdocs.viewer.results.Layer> | Katmanların listesi. |
| düzenler | java.util.List<com.groupdocs.viewer.results.Layout> | Düzenlerin listesi. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Belirtilen dosya türü, sayfalar, başlangıç tarihi ve bitiş tarihi ile [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Sayfaların listesi. |
| startDate | java.util.Date | Başlangıç tarihi. |
| endDate | java.util.Date | Bitiş tarihi. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Belirtilen değer, koordinatlar ve boyutlarla [TextElement](../../com.groupdocs.viewer.results/textelement) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | Değer. |
| x | double | X koordinatı. |
| y | double | Y koordinatı. |
| width | double | Genişlik. |
| height | double | Yükseklik. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Belirtilen dosya türü, sayfalar ve not sayısı ile MboxViewInfo arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Dosyanın türü. |
| sayfalar | java.util.List<com.groupdocs.viewer.results.Page> | Görüntülenecek sayfaların listesi. |
| notesCount | int | Lotus veritabanı depolama dosyasında bulunan not sayısı. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo uygulamasının yeni bir örneği.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Belirtilen kelime, koordinatlar, boyutlar ve karakterlerle [Word](../../com.groupdocs.viewer.results/word) arayüzünün bir uygulamasını oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kelime | java.lang.String | Kelime. |
| x | double | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın X koordinatı. |
| y | double | Kelimeyi içeren dikdörtgenin başladığı sayfa düzenindeki en üst sol noktanın Y koordinatı. |
| width | double | Kelimeyi içeren dikdörtgenin genişliği (piksel cinsinden). |
| height | double | Kelimeyi içeren dikdörtgenin yüksekliği (piksel cinsinden). |
| karakterler | java.util.List<com.groupdocs.viewer.results.Character> | Kelimeyi içeren karakterler. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
