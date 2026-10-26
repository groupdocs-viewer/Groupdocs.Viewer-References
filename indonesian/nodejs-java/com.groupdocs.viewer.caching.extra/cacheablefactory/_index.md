---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Kelas ini membantu menyesuaikan ."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Kelas ini membantu menyesuaikan [Cache](../../com.groupdocs.viewer.caching/cache).

Model khusus untuk serialisasi dapat diimplementasikan dengan menimpa metode dalam kelas ini untuk mengembalikannya alih-alih yang tersemat. Untuk mencapai ini, perpanjang CacheableFactory dan aktifkan dengan memberikan instance baru dari pabrik khusus ke metode [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-).

Contoh penggunaan:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

Untuk detail lebih lanjut, panduan, dan contoh tentang menyesuaikan cache, silakan merujuk ke [GroupDocs.Viewer documentation][].


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInstance()](#getInstance--) | Mendapatkan instance dari  CacheableFactory  yang dapat digunakan untuk membuat objek yang dapat di-cache. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Menetapkan instance dari  CacheableFactory  yang akan digunakan. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Membuat implementasi dari antarmuka [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) untuk tipe file dan halaman yang ditentukan. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Membuat implementasi dari antarmuka [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) untuk tipe file, halaman, dan jumlah catatan yang ditentukan. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Membuat implementasi dari antarmuka [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) untuk tipe file, halaman, dan folder yang ditentukan. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Membuat implementasi dari antarmuka [Character](../../com.groupdocs.viewer.results/character) untuk karakter, posisi, dan dimensi yang ditentukan. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Membuat implementasi dari antarmuka [FileInfo](../../com.groupdocs.viewer.results/fileinfo) untuk tipe file yang ditentukan. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Membuat implementasi dari antarmuka [Layer](../../com.groupdocs.viewer.results/layer) dengan nama dan visibilitas yang ditentukan. |
| [newLayer(String name)](#newLayer-java.lang.String-) | Membuat implementasi dari antarmuka [Layer](../../com.groupdocs.viewer.results/layer) dengan nama yang ditentukan. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Membuat implementasi dari antarmuka [Layout](../../com.groupdocs.viewer.results/layout) dengan nama, lebar, dan tinggi yang ditentukan. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Membuat implementasi dari antarmuka [Line](../../com.groupdocs.viewer.results/line) dengan baris, posisi, dimensi, dan kata yang ditentukan. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Membuat implementasi dari antarmuka [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) berdasarkan tipe file, daftar halaman, dan daftar folder yang ditentukan. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor dan visibilitas yang ditentukan. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor, nama, dan visibilitas yang ditentukan. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor, nama, visibilitas, lebar, dan tinggi yang ditentukan. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, visibilitas, lebar, dan tinggi yang ditentukan. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, nama, visibilitas, lebar, tinggi, dan baris yang ditentukan. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, visibilitas, lebar, tinggi, dan baris yang ditentukan. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Membuat implementasi dari antarmuka [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) dengan tipe file, halaman, dan flag izin pencetakan yang ditentukan. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Membuat implementasi dari antarmuka [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) dengan tipe file, halaman, lapisan, dan tata letak yang ditentukan. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Membuat implementasi dari antarmuka [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) dengan tipe file, halaman, tanggal mulai, dan tanggal selesai yang ditentukan. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Membuat implementasi dari antarmuka [TextElement](../../com.groupdocs.viewer.results/textelement) dengan nilai, koordinat, dan dimensi yang ditentukan. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Membuat implementasi dari antarmuka MboxViewInfo dengan tipe file, halaman, dan jumlah catatan yang ditentukan. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Membuat implementasi dari antarmuka [Word](../../com.groupdocs.viewer.results/word) dengan kata, koordinat, dimensi, dan karakter yang ditentukan. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Mendapatkan instance dari  CacheableFactory  yang dapat digunakan untuk membuat objek yang dapat di-cache.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Mengatur instance dari  CacheableFactory  yang akan digunakan. Ini memungkinkan implementasi khusus dari pabrik cacheable.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Instance dari  CacheableFactory  yang akan diatur. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Membuat implementasi dari antarmuka [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) untuk tipe file dan halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman yang mewakili halaman dokumen. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Membuat implementasi dari antarmuka [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) untuk tipe file, halaman, dan jumlah catatan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman yang mewakili halaman dokumen. |
| notesCount | int | Jumlah Lotus Notes dalam dokumen. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Membuat implementasi dari antarmuka [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) untuk tipe file, halaman, dan folder yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman yang mewakili halaman dokumen. |
| folder | java.util.List<java.lang.String> | Daftar folder dalam arsip. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Membuat implementasi dari antarmuka [Character](../../com.groupdocs.viewer.results/character) untuk karakter, posisi, dan dimensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| karakter | char | Karakter tersebut. |
| x | double | Koordinat x dari posisi karakter. |
| y | double | Koordinat y dari posisi karakter. |
| width | double | Lebar karakter. |
| height | double | Tinggi karakter. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Membuat implementasi dari antarmuka [FileInfo](../../com.groupdocs.viewer.results/fileinfo) untuk tipe file yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Membuat implementasi dari antarmuka [Layer](../../com.groupdocs.viewer.results/layer) dengan nama dan visibilitas yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama lapisan. |
| terlihat | boolean | Visibilitas lapisan. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Membuat implementasi dari antarmuka [Layer](../../com.groupdocs.viewer.results/layer) dengan nama yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama lapisan. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Membuat implementasi dari antarmuka [Layout](../../com.groupdocs.viewer.results/layout) dengan nama, lebar, dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama tata letak. |
| width | double | Lebar tata letak. |
| height | double | Tinggi tata letak. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Membuat implementasi dari antarmuka [Line](../../com.groupdocs.viewer.results/line) dengan baris, posisi, dimensi, dan kata yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| garis | java.lang.String | Konten garis. |
| x | double | Koordinat X titik kiri-atas dari persegi panjang yang berisi garis. |
| y | double | Koordinat Y titik kiri-atas dari persegi panjang yang berisi garis. |
| width | double | Lebar persegi panjang yang berisi garis (dalam piksel). |
| height | double | Tinggi persegi panjang yang berisi garis (dalam piksel). |
| kata | java.util.List<com.groupdocs.viewer.results.Word> | Kata-kata yang terdapat dalam garis. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama lampiran. |
| filePath | java.lang.String | Jalur relatif lampiran, misalnya "folder/file.docx". Ketika file berada di root arsip, dalam pesan email, atau file data, tentukan nama file. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | java.lang.String | ID lampiran. |
| fileName | java.lang.String | Nama lampiran. |
| filePath | java.lang.String | Jalur relatif lampiran, misalnya "folder/file.docx". Ketika file berada di root arsip, dalam pesan email, atau file data, tentukan nama file. |
| ukuran | long | Ukuran lampiran. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | java.lang.String | ID lampiran. |
| fileName | java.lang.String | Nama lampiran. |
| filePath | java.nio.file.Path | Jalur relatif atau absolut lampiran. |
| ukuran | long | Ukuran lampiran. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Membuat implementasi dari antarmuka [Attachment](../../com.groupdocs.viewer.results/attachment). Lampiran mewakili file yang terlampir pada dokumen atau pesan email.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| id | java.lang.String | ID lampiran. |
| fileName | java.lang.String | Nama lampiran. |
| filePath | java.lang.String | Jalur relatif atau absolut dari lampiran. Itu dapat berupa jalur file dalam folder atau nama file itu sendiri jika file berada di akar arsip, dalam pesan email, atau dalam file data. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file lampiran. |
| ukuran | long | Ukuran lampiran. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Membuat implementasi dari antarmuka [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) berdasarkan tipe file, daftar halaman, dan daftar folder yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman. |
| folder | java.util.List<java.lang.String> | Daftar folder. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor dan visibilitas yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| terlihat | boolean | Bendera visibilitas. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor, nama, dan visibilitas yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| nama | java.lang.String | Nama halaman. |
| terlihat | boolean | Bendera visibilitas. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang merepresentasikan halaman dengan nomor, nama, visibilitas, lebar, dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| nama | java.lang.String | Nama halaman. |
| terlihat | boolean | Bendera visibilitas. |
| width | int | Lebar halaman. |
| height | int | Tinggi halaman. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, visibilitas, lebar, dan tinggi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| terlihat | boolean | Bendera visibilitas. |
| width | int | Lebar halaman. |
| height | int | Tinggi halaman. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, nama, visibilitas, lebar, tinggi, dan baris yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| nama | java.lang.String | Nama halaman. |
| terlihat | boolean | Bendera visibilitas. |
| width | int | Lebar halaman. |
| height | int | Tinggi halaman. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | Baris-baris yang terdapat dalam halaman. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Membuat implementasi dari antarmuka [Page](../../com.groupdocs.viewer.results/page) yang mewakili halaman dengan nomor, visibilitas, lebar, tinggi, dan baris yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | Nomor halaman. |
| terlihat | boolean | Bendera visibilitas. |
| width | int | Lebar halaman. |
| height | int | Tinggi halaman. |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | Baris-baris yang terdapat dalam halaman. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Membuat implementasi dari antarmuka [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) dengan tipe file, halaman, dan flag izin pencetakan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman. |
| printingAllowed | boolean | Bendera yang menunjukkan apakah pencetakan diizinkan. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Membuat implementasi dari antarmuka [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) dengan tipe file, halaman, lapisan, dan tata letak yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman. |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | Daftar lapisan. |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | Daftar tata letak. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Membuat implementasi dari antarmuka [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) dengan tipe file, halaman, tanggal mulai, dan tanggal selesai yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Tipe file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman. |
| startDate | java.util.Date | Tanggal mulai. |
| endDate | java.util.Date | Tanggal akhir. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Membuat implementasi dari antarmuka [TextElement](../../com.groupdocs.viewer.results/textelement) dengan nilai, koordinat, dan dimensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai. |
| x | double | Koordinat X. |
| y | double | Koordinat Y. |
| width | double | Lebar. |
| height | double | Tinggi. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Membuat implementasi dari antarmuka MboxViewInfo dengan tipe file, halaman, dan jumlah catatan yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Jenis file. |
| halaman | java.util.List<com.groupdocs.viewer.results.Page> | Daftar halaman untuk dilihat. |
| notesCount | int | Jumlah catatan yang terdapat dalam file penyimpanan basis data Lotus. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - sebuah instance baru dari implementasi MboxViewInfo.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Membuat implementasi dari antarmuka [Word](../../com.groupdocs.viewer.results/word) dengan kata, koordinat, dimensi, dan karakter yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata | java.lang.String | Kata. |
| x | double | Koordinat X dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi kata dimulai. |
| y | double | Koordinat Y dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi kata dimulai. |
| width | double | Lebar persegi panjang yang berisi kata (dalam piksel). |
| height | double | Tinggi persegi panjang yang berisi kata (dalam piksel). |
| karakter | java.util.List<com.groupdocs.viewer.results.Character> | Karakter yang terdapat dalam kata. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
