---
title: "WordProcessingOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender dokumen pengolah kata."
type: docs
weight: 38
url: /id/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Menyediakan opsi untuk merender dokumen pengolah kata.


Kelas WordProcessingOptions menyediakan opsi untuk merender dokumen pengolah kata
dalam komponen GroupDocs.Viewer. Ini mengenkapsulasi pengaturan dan parameter yang dapat digunakan
untuk mengontrol proses rendering dan format output untuk file pengolah kata.
Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Contoh penggunaan:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Menginisialisasi instance baru dari |
WordProcessingOptions
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Mengambil ukuran halaman untuk merender file HTM dan HTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Mengatur ukuran halaman untuk merender file HTM dan HTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Menunjukkan apakah rendering perubahan yang dilacak (revisi) diaktifkan. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Mengatur apakah rendering perubahan yang dilacak (revisi) diaktifkan. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Mengambil margin kiri halaman untuk rendering HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Mengatur margin kiri halaman untuk rendering HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | Mengambil margin kanan halaman untuk rendering HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Mengatur margin kanan halaman untuk rendering HTML. |
|
|  | [getTopMargin()](#getTopMargin--) | Mengambil margin atas halaman untuk rendering HTML. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Mengatur margin atas halaman untuk rendering HTML. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Margin bawah halaman (hanya untuk rendering HTML) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Mengatur margin bawah halaman untuk rendering HTML. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Opsi ini mengaktifkan kerning dan fitur OpenType lainnya saat merender skrip Arab, Ibrani, India, berbasis Latin, atau berbasis Sirilik. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Opsi ini mengaktifkan kerning dan fitur OpenType lainnya saat merender skrip Arab, Ibrani, India, berbasis Latin, atau berbasis Sirilik. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Menunjukkan apakah navigasi daftar isi harus dinonaktifkan saat merender ke HTML atau PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Mengatur apakah navigasi daftar isi harus dinonaktifkan saat merender ke HTML atau PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Mendapatkan nilai yang menentukan apakah bidang tertentu harus diperbarui sebelum menyimpan dokumen WordProcessing input ke format output HTML, PDF, PNG, atau JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Mengatur nilai yang menentukan apakah bidang tertentu harus diperbarui sebelum menyimpan dokumen WordProcessing input ke format output HTML, PDF, PNG, atau JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Mendapatkan resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Mengatur resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Mendapatkan resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Mengatur resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Memungkinkan penerapan penomoran halaman secara paksa untuk dokumen WordProcessing yang dimuat. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Memungkinkan penerapan penomoran halaman secara paksa untuk dokumen WordProcessing yang dimuat. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Periksa apakah opsi telah berubah. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Menginisialisasi instance baru dari
WordProcessingOptions
kelas.
Berisi opsi untuk merender dokumen pengolah kata. Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Mengambil ukuran halaman untuk merender file HTM dan HTML.


Saat menggunakan ukuran halaman default, beberapa konten mungkin tidak muat dalam bingkai halaman.
Untuk menyesuaikan konten, Anda dapat mengatur ukuran halaman yang lebih besar, seperti A3, menggunakan [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Mengatur ukuran halaman untuk merender file HTM dan HTML.


Saat menggunakan ukuran halaman default, beberapa konten mungkin tidak muat dalam bingkai halaman.
Untuk menyesuaikan konten, Anda dapat mengatur ukuran halaman yang lebih besar, seperti A3, menggunakan [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Ukuran halaman output. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Menunjukkan apakah rendering perubahan yang dilacak (revisi) diaktifkan.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  jika rendering perubahan terlacak diaktifkan,  false  sebaliknya.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Mengatur apakah rendering perubahan yang dilacak (revisi) diaktifkan.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  untuk mengaktifkan rendering perubahan terlacak,  false  untuk menonaktifkannya. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Mengambil margin kiri halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - nilai margin kiri halaman.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Mengatur margin kiri halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Nilai margin kiri halaman yang akan diatur. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Mengambil margin kanan halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - nilai margin halaman kanan.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Mengatur margin kanan halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Nilai margin halaman kanan yang akan diatur. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Mengambil margin atas halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - margin halaman atas.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Mengatur margin atas halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Margin halaman atas yang akan diatur. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Margin bawah halaman (hanya untuk rendering HTML)
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - margin halaman bawah.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Mengatur margin bawah halaman untuk rendering HTML.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Margin halaman bawah yang akan diatur. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Opsi ini mengaktifkan kerning dan fitur OpenType lainnya saat merender skrip Arab, Ibrani, India, berbasis Latin, atau berbasis Sirilik.


**Returns:**
boolean - True jika fitur OpenType diaktifkan, false jika tidak.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Opsi ini mengaktifkan kerning dan fitur OpenType lainnya saat merender skrip Arab, Ibrani, India, berbasis Latin, atau berbasis Sirilik.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | True untuk mengaktifkan fitur OpenType, false jika tidak. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Menunjukkan apakah navigasi daftar isi harus dinonaktifkan saat merender ke HTML atau PDF. Ketika opsi ini diatur ke true, untuk rendering HTML, tautan relatif dari daftar isi akan diganti dengan tag span, menghapus fungsionalitas tetapi mempertahankan tampilan visual. Untuk rendering PDF, daftar isi akan dirender sebagai teks biasa tanpa tautan.


**Returns:**
boolean - True jika navigasi daftar isi dinonaktifkan; jika tidak, false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Mengatur apakah navigasi daftar isi harus dinonaktifkan saat merender ke HTML atau PDF. Ketika opsi ini diatur ke true, untuk rendering HTML, tautan relatif dari daftar isi akan diganti dengan tag span, menghapus fungsionalitas tetapi mempertahankan tampilan visual. Untuk rendering PDF, daftar isi akan dirender sebagai teks biasa tanpa tautan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Menunjukkan apakah navigasi daftar isi harus dinonaktifkan. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Mendapatkan nilai yang menentukan apakah bidang dengan tipe tertentu harus diperbarui sebelum menyimpan dokumen WordProcessing input ke format output HTML, PDF, PNG, atau JPEG. Nilai default untuk properti ini adalah true — bidang akan diperbarui sebelum penyimpanan.


Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Mengatur nilai yang menentukan apakah bidang dengan tipe tertentu harus diperbarui sebelum menyimpan dokumen WordProcessing input ke format output HTML, PDF, PNG, atau JPEG. Nilai default untuk properti ini adalah true — bidang akan diperbarui sebelum penyimpanan.


Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Mendapatkan resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini digunakan hanya saat merender dokumen WordProcessing ke format PNG atau JPEG.


Nilai default adalah 96 DPI. Nilai minimum yang memungkinkan - 72 DPI, nilai maksimum yang memungkinkan - 600 DPI.
Jika nilai yang ditentukan pengguna berada di luar batas ini, nilai minimum atau maksimum yang memungkinkan akan diterapkan.


**Returns:**
int - resolusi horizontal dalam DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Mengatur resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini digunakan hanya saat merender dokumen WordProcessing ke format PNG atau JPEG.


Nilai default adalah 96 DPI. Nilai minimum yang memungkinkan - 72 DPI, nilai maksimum yang memungkinkan - 600 DPI.
Jika nilai yang ditentukan pengguna berada di luar batas ini, nilai minimum atau maksimum yang memungkinkan akan diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | horizontalResolution | int | resolusi horizontal dalam DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Mendapatkan resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini digunakan hanya saat merender dokumen WordProcessing ke format PNG atau JPEG.


Nilai default adalah 96 DPI. Nilai minimum yang memungkinkan - 72 DPI, nilai maksimum yang memungkinkan - 600 DPI.
Jika nilai yang ditentukan pengguna berada di luar batas ini, nilai minimum atau maksimum yang memungkinkan akan diterapkan.


**Returns:**
int - resolusi vertikal dalam DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Mengatur resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini digunakan hanya saat merender dokumen WordProcessing ke format PNG atau JPEG.


Nilai default adalah 96 DPI. Nilai minimum yang memungkinkan - 72 DPI, nilai maksimum yang memungkinkan - 600 DPI.
Jika nilai yang ditentukan pengguna berada di luar batas ini, nilai minimum atau maksimum yang memungkinkan akan diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | verticalResolution | int | resolusi vertikal dalam DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Memungkinkan untuk memaksa menerapkan penomoran halaman pada dokumen WordProcessing yang dimuat. Secara default adalah [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) — dokumen tetap utuh.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Memungkinkan untuk memaksa menerapkan penomoran halaman pada dokumen WordProcessing yang dimuat. Secara default adalah [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) — dokumen tetap utuh.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | lokasi nomor halaman. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Periksa apakah opsi telah berubah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | o | java.lang.Object | Objek untuk dibandingkan kesetaraannya. |
|

**Returns:**
boolean -  true  jika opsi sama dengan objek yang ditentukan,  false  sebaliknya.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menghitung nilai kode hash untuk objek ini. Kode hash didasarkan pada
status internal objek dan digunakan dalam struktur data berbasis hash
seperti peta hash dan set hash.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - nilai kode hash untuk objek ini.

