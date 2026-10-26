---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender dokumen ke format JPG."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Menyediakan opsi untuk merender dokumen ke format JPG.

Kelas JpgViewOptions mengenkapsulasi pengaturan tambahan dan parameter yang dapat digunakan untuk mengontrol rendering dokumen ke format JPG dalam komponen GroupDocs.Viewer.

Contoh penggunaan:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Menginisialisasi instance baru dari kelas JpgViewOptions. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Menginisialisasi instance baru dari kelas JpgViewOptions. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Menginisialisasi instance baru dari kelas JpgViewOptions. |
| [JpgViewOptions()](#JpgViewOptions--) | Menginisialisasi instance baru dari JpgViewOptions dengan "p\\_\\{0\\}.jpg" sebagai format jalur file untuk file output. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas JpgViewOptions. |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas JpgViewOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Mendapatkan lebar maksimum gambar output dalam piksel. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Mengatur lebar maksimum gambar output dalam piksel. |
| [getMaxHeight()](#getMaxHeight--) | Mendapatkan tinggi maksimum gambar output dalam piksel. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Mengatur tinggi maksimum gambar output dalam piksel. |
| [getQuality()](#getQuality--) | Mendapatkan kualitas gambar output. |
| [setQuality(byte value)](#setQuality-byte-) | Menetapkan kualitas gambar output. |
| [isExtractText()](#isExtractText--) | Mengaktifkan ekstraksi teks. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Mengaktifkan atau menonaktifkan ekstraksi teks. |
| [getWidth()](#getWidth--) | Mendapatkan lebar gambar output dalam piksel. |
| [setWidth(int value)](#setWidth-int-) | Mengatur lebar gambar output dalam piksel. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi gambar output dalam piksel. |
| [setHeight(int value)](#setHeight-int-) | Menetapkan tinggi gambar keluaran dalam piksel. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Mendapatkan pabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Mendapatkan callback untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Menetapkan callback untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas JpgViewOptions.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas JpgViewOptions.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diberikan ke parameter createPageStream. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Menginisialisasi instance baru dari kelas JpgViewOptions.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Menginisialisasi instance baru dari JpgViewOptions dengan "p\\_\\{0\\}.jpg" sebagai format jalur file untuk file output. File output akan ditempatkan ke direktori kerja saat ini dari aplikasi.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Menginisialisasi instance baru dari kelas JpgViewOptions.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'page\\_\\{0\\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Menginisialisasi instance baru dari kelas JpgViewOptions.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Format jalur file, misalnya 'page\\_\\{0\\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Mendapatkan lebar maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti \\#setWidth(int).setWidth(int), properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - lebar maksimum gambar output.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Mengatur lebar maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti \\#setWidth(int).setWidth(int), properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxWidth | int | Lebar maksimum gambar output. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Mendapatkan tinggi maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti \#setHeight(int).setHeight(int), properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - tinggi maksimum gambar output.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Mengatur tinggi maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti \#setHeight(int).setHeight(int), properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxHeight | int | Tinggi maksimum gambar output. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Mendapatkan kualitas gambar output.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - kualitas gambar output.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Menetapkan kualitas gambar output.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte | Kualitas gambar output. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Mengaktifkan ekstraksi teks.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  jika ekstraksi teks diaktifkan,  false  jika tidak.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Mengaktifkan atau menonaktifkan ekstraksi teks.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan ekstraksi teks,  false  untuk menonaktifkannya. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti \#setMaxWidth(int).setMaxWidth(int) akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - lebar gambar output.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti \#setMaxWidth(int).setMaxWidth(int) akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Lebar gambar output. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti \#setMaxHeight(int).setMaxHeight(int) akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - tinggi gambar output.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Menetapkan tinggi gambar keluaran dalam piksel.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti \#setMaxHeight(int).setMaxHeight(int) akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Tinggi gambar output. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Mendapatkan pabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Mendapatkan callback untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - callback untuk memperkirakan kemajuan penyimpanan dokumen.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Menetapkan callback untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Callback untuk memperkirakan kemajuan penyimpanan dokumen. |

