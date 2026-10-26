---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender dokumen ke format PDF."
type: docs
weight: 23
url: /id/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Menyediakan opsi untuk merender dokumen ke format PDF.

Kelas PdfViewOptions mengenkapsulasi pengaturan tambahan dan parameter yang dapat digunakan untuk mengontrol rendering dokumen ke format PDF dalam komponen GroupDocs.Viewer. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Menginisialisasi instance baru dari kelas  PdfViewOptions  . |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Menginisialisasi instance baru dari kelas  PdfViewOptions  . |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Menginisialisasi instance baru dari kelas  PdfViewOptions  . |
| [PdfViewOptions()](#PdfViewOptions--) | Menginisialisasi instance baru dari kelas  PdfViewOptions  dengan pengaturan default. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas  PdfViewOptions  . |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas  PdfViewOptions  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Kurangi ukuran file PDF output dengan menerapkan teknik optimasi dengan opsi yang berbeda. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Kurangi ukuran file PDF output dengan menerapkan teknik optimasi dengan opsi yang berbeda. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Mengambil lebar maksimum gambar output dalam piksel. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Mengatur lebar maksimum gambar output dalam piksel. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Mengambil tinggi maksimum gambar output dalam piksel. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Mengatur tinggi maksimum gambar output dalam piksel. |
| [getImageWidth()](#getImageWidth--) | Mengambil lebar gambar output dalam piksel. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Mengatur lebar gambar output dalam piksel. |
| [getImageHeight()](#getImageHeight--) | Mengambil tinggi gambar keluaran dalam piksel. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Menetapkan tinggi gambar keluaran dalam piksel. |
| [getSecurity()](#getSecurity--) | Mengambil opsi keamanan untuk dokumen PDF keluaran. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Menetapkan opsi keamanan untuk dokumen PDF keluaran. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Mengambil callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Menetapkan callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Metode yang digunakan untuk menginstansiasi stream untuk menulis data file keluaran. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Metode yang digunakan untuk melepaskan stream yang dibuat oleh metode  createFileStream . |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Pabrik yang mengimplementasikan metode untuk membuat dan melepaskan stream file keluaran. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  dengan pengaturan default.

Konstruktor ini membuat objek  PdfViewOptions  baru dengan "output.pdf" sebagai format jalur file untuk file keluaran. File keluaran akan ditempatkan ke direktori kerja saat ini dari aplikasi. Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  .

Konstruktor ini membuat objek  PdfViewOptions  baru dengan parameter  outputFilePath  yang ditentukan, mewakili jalur untuk file PDF keluaran. Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFilePath | java.lang.String | Jalur untuk file PDF keluaran. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Menginisialisasi instance baru dari kelas  PdfViewOptions  .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Jalur untuk file PDF keluaran. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Kurangi ukuran file PDF output dengan menerapkan teknik optimasi dengan opsi yang berbeda.

Opsi ini didukung untuk semua format file input yang didukung untuk konversi ke PDF: [Format dokumen yang didukung][] Untuk detail dan contoh kode, lihat [halaman][] ini dan turunannya.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Kurangi ukuran file PDF output dengan menerapkan teknik optimasi dengan opsi yang berbeda.

Opsi ini didukung untuk semua format file input yang didukung untuk konversi ke PDF: [Format dokumen yang didukung][] Untuk detail dan contoh kode, lihat [halaman][] ini dan turunannya.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Objek PdfOptimizationOptions atau null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Mengambil lebar maksimum gambar keluaran dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk menetapkan lebar maksimum gambar keluaran (dalam piksel). GroupDocs.Viewer menerapkan properti ini saat merender satu gambar ke PDF. Untuk detail, lihat [dokumentasi][]. Jika Anda mengatur properti  , properti ini diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - lebar maksimum gambar keluaran dalam piksel.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Menetapkan lebar maksimum gambar keluaran dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk menetapkan lebar maksimum gambar keluaran (dalam piksel). GroupDocs.Viewer menerapkan properti ini saat merender satu gambar ke PDF. Untuk detail, lihat [dokumentasi][]. Jika Anda mengatur properti  , properti ini diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageMaxWidth | int | Lebar maksimum gambar keluaran dalam piksel. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Mengambil tinggi maksimum gambar keluaran dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk menetapkan tinggi maksimum gambar keluaran (dalam piksel). GroupDocs.Viewer menerapkan properti ini saat merender satu gambar ke PDF. Untuk detail, lihat [dokumentasi][]. Jika Anda mengatur properti  , properti ini diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - tinggi maksimum gambar keluaran dalam piksel.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Mengatur tinggi maksimum gambar output dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). GroupDocs.Viewer menerapkan properti ini hanya saat merender satu gambar ke HTML. Untuk detail, lihat [documentation][]. Jika Anda mengatur properti  , properti ini diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageMaxHeight | int | Tinggi maksimum gambar output dalam piksel. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Mengambil lebar gambar output dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). GroupDocs.Viewer menerapkan properti ini saat merender satu gambar ke PDF. Untuk detail, lihat [documentation][]. Jika Anda mengatur properti ini, properti  diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - lebar gambar output dalam piksel.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Mengatur lebar gambar output dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar PDF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageWidth | int | Lebar gambar output dalam piksel. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Mengambil tinggi gambar output dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). GroupDocs.Viewer menerapkan properti ini hanya saat merender satu gambar ke HTML. Untuk detail, lihat [documentation][]. Jika Anda mengatur properti ini, properti  diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - tinggi gambar output dalam piksel.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Mengatur tinggi gambar output dalam piksel. Parameter ini hanya berlaku saat mengonversi satu gambar ke HTML.

Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). GroupDocs.Viewer menerapkan properti ini hanya saat merender satu gambar ke HTML. Untuk detail, lihat [documentation][]. Jika Anda mengatur properti ini, properti  diabaikan.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageHeight | int | Tinggi gambar output dalam piksel. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Mengambil opsi keamanan untuk dokumen PDF keluaran.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Menetapkan opsi keamanan untuk dokumen PDF keluaran.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Opsi keamanan untuk dokumen PDF output. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Mengambil callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - callback untuk memperkirakan kemajuan penyimpanan dokumen.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Menetapkan callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Callback untuk memperkirakan kemajuan penyimpanan dokumen. |

