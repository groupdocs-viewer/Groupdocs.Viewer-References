---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender dokumen ke format PNG."
type: docs
weight: 25
url: /id/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Menyediakan opsi untuk merender dokumen ke format PNG.

Kelas PngViewOptions mengenkapsulasi pengaturan tambahan dan parameter yang dapat digunakan untuk mengontrol rendering dokumen ke format PNG dalam komponen GroupDocs.Viewer.

Contoh penggunaan:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
| [PngViewOptions()](#PngViewOptions--) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas  PngViewOptions . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Mengembalikan lebar maksimum gambar output dalam piksel. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Mengatur lebar maksimum gambar output dalam piksel. |
| [getMaxHeight()](#getMaxHeight--) | Mengembalikan tinggi maksimum gambar output dalam piksel. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Mengatur tinggi maksimum gambar output dalam piksel. |
| [isExtractText()](#isExtractText--) | Menentukan apakah ekstraksi teks diaktifkan. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Mengaktifkan atau menonaktifkan ekstraksi teks. |
| [getWidth()](#getWidth--) | Mengembalikan lebar gambar output dalam piksel. |
| [setWidth(int value)](#setWidth-int-) | Mengatur lebar gambar output dalam piksel. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi gambar output dalam piksel. |
| [setHeight(int value)](#setHeight-int-) | Menetapkan tinggi gambar keluaran dalam piksel. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Mengambil callback untuk memperkirakan kemajuan penyimpanan dokumen. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Mengatur callback untuk memperkirakan kemajuan penyimpanan dokumen. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metode yang melepaskan stream yang dibuat oleh metode yang ditetapkan pada parameter createPageStream. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Konstruktor ini menginisialisasi instance baru dari PngViewOptions dengan "p\_\{0\}.png" sebagai format jalur file untuk file output. File output akan ditempatkan di direktori kerja saat ini aplikasi. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Sebagai contoh, jika format jalur file adalah 'page\_\{0\}.png', file output akan dinamai 'page\_1.png', 'page\_2.png', dan seterusnya, berdasarkan nomor halaman.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Menginisialisasi instance baru dari kelas  PngViewOptions .

Sebagai contoh, jika format jalur file adalah 'page\_\{0\}.png', file output akan dinamai 'page\_1.png', 'page\_2.png', dan seterusnya, berdasarkan nomor halaman. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Format jalur file, misalnya 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Mengembalikan lebar maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti  , properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - lebar maksimum gambar output.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Mengatur lebar maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti  , properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxWidth | int | Lebar maksimum gambar output. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Mengembalikan tinggi maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti  , properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - tinggi maksimum gambar output.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Mengatur tinggi maksimum gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti  , properti ini akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxHeight | int | Tinggi maksimum gambar output. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Menentukan apakah ekstraksi teks diaktifkan.

Opsi ini mungkin berguna ketika Anda ingin menambahkan lapisan teks yang dapat dipilih di atas gambar. Gunakan properti ini untuk mendapatkan teks yang terdapat dalam dokumen sumber beserta koordinatnya. Kemudian Anda dapat menggunakan data ini untuk menambahkan teks yang dapat dipilih di atas gambar atau untuk mengimplementasikan pencarian teks dalam rendering berbasis gambar. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  jika ekstraksi teks diaktifkan,  false  jika tidak.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Mengaktifkan atau menonaktifkan ekstraksi teks.

Opsi ini mungkin berguna ketika Anda ingin menambahkan lapisan teks yang dapat dipilih di atas gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan ekstraksi teks,  false  untuk menonaktifkannya. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mengembalikan lebar gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti  akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - lebar gambar output.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Mengatur lebar gambar output dalam piksel.

Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti  akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Lebar gambar output. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mengembalikan tinggi gambar output dalam piksel.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti  akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - tinggi gambar output.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Menetapkan tinggi gambar keluaran dalam piksel.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [documentation][]. Jika Anda mengatur properti ini, properti  akan diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Tinggi gambar output. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Mengambil callback untuk memperkirakan kemajuan penyimpanan dokumen.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - callback untuk memperkirakan kemajuan penyimpanan dokumen.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Mengatur callback untuk memperkirakan kemajuan penyimpanan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Callback untuk memperkirakan kemajuan penyimpanan dokumen. |

