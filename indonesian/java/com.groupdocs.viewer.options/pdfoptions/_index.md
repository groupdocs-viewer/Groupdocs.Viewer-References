---
title: "PdfOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender dokumen PDF."
type: docs
weight: 22
url: /id/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Menyediakan opsi untuk merender dokumen PDF.


Kelas PdfOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan
untuk mengontrol perenderan dokumen PDF dalam komponen GroupDocs.Viewer.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Contoh penggunaan:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Menginisialisasi instance baru dari |
PdfOptions
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Menonaktifkan perlindungan penyalinan konten saat merender ke HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Menonaktifkan perlindungan penyalinan konten saat merender ke HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Menentukan apakah teks dari sumber dirender sebagai gambar dalam HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Mengatur apakah teks dari sumber dirender sebagai gambar dalam HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Memeriksa apakah pengelompokan karakter dinonaktifkan untuk mempertahankan presisi maksimum selama penempatan karakter saat merender halaman. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Mengatur opsi untuk menonaktifkan pengelompokan karakter, memastikan presisi maksimum selama penempatan karakter saat merender halaman. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Memeriksa apakah perenderan teks dan grafik harus mengikuti urutan z dalam dokumen PDF asli saat merender ke HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Mengaktifkan atau menonaktifkan perenderan teks dan grafik sesuai urutan z dalam dokumen PDF asli saat merender ke HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Menentukan apakah hinting font diaktifkan. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Mengaktifkan hinting font. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber. |
|
|  | [getImageQuality()](#getImageQuality--) | Mengambil kualitas gambar output untuk sumber daya gambar saat merender ke HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Mengatur kualitas gambar output untuk sumber daya gambar saat merender ke HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG untuk meningkatkan kualitas output. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG untuk meningkatkan kualitas output. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Setel flag untuk menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Menginisialisasi instance baru dari
PdfOptions
kelas.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Menonaktifkan perlindungan penyalinan konten saat merender ke HTML.


Saat merender file PDF dengan perlindungan terhadap penyalinan teks dan gambar ke HTML, GroupDocs.Viewer menambahkan atribut HTML 'inert' ke tag HTML BODY.
Nilai default dari opsi ini adalah
false
.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Menonaktifkan perlindungan penyalinan konten saat merender ke HTML.


Saat merender file PDF dengan perlindungan terhadap penyalinan teks dan gambar ke HTML, GroupDocs.Viewer menambahkan atribut HTML 'inert' ke tag HTML BODY.
Nilai default dari opsi ini adalah
false
.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Menentukan apakah teks dari sumber dirender sebagai gambar dalam HTML.


Ketika opsi ini diatur ke
true
, teks dirender sebagai gambar dalam HTML output.
Aktifkan opsi ini untuk membuat teks tidak dapat dipilih atau untuk memperbaiki perenderan karakter dan membuat HTML terlihat seperti PDF.
Opsi ini didukung saat merender ke HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika teks dirender sebagai gambar dalam HTML,  false  sebaliknya.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Mengatur apakah teks dari sumber dirender sebagai gambar dalam HTML.


Ketika opsi ini diatur ke
true
, teks dirender sebagai gambar dalam HTML output.
Aktifkan opsi ini untuk membuat teks tidak dapat dipilih atau untuk memperbaiki perenderan karakter dan membuat HTML terlihat seperti PDF.
Opsi ini didukung saat merender ke HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  untuk merender teks sebagai gambar dalam HTML,  false  sebaliknya. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Memeriksa apakah pengelompokan karakter dinonaktifkan untuk mempertahankan presisi maksimum selama penempatan karakter saat merender halaman.
Ketika opsi ini diaktifkan, karakter dirender tanpa pengelompokan apa pun, yang memastikan presisi maksimum.


***Note:** By default, character grouping is enabled.*
Ketika mengonversi file PDF, GroupDocs.Viewer mengelompokkan karakter individual menjadi kata untuk meningkatkan kinerja rendering. Jika dokumen Anda mencakup hieroglif atau simbol khusus, Anda mungkin ingin melarang pengelompokan karakter untuk memastikan tata letak yang lebih tepat. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  jika pengelompokan karakter dinonaktifkan,  false  sebaliknya.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Mengatur opsi untuk menonaktifkan pengelompokan karakter, memastikan presisi maksimum selama penempatan karakter saat merender halaman.
Ketika opsi ini diaktifkan dengan mengatur nilai ke
true
, pengelompokan karakter dinonaktifkan, yang memastikan presisi maksimum.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Ketika mengonversi file PDF, GroupDocs.Viewer mengelompokkan karakter individual menjadi kata untuk meningkatkan kinerja rendering. Jika dokumen Anda mencakup hieroglif atau simbol khusus, Anda mungkin ingin melarang pengelompokan karakter untuk memastikan tata letak yang lebih tepat. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  untuk menonaktifkan pengelompokan karakter,  false  untuk mengaktifkannya. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Memeriksa apakah perenderan teks dan grafik harus mengikuti urutan z dalam dokumen PDF asli saat merender ke HTML.
Ketika opsi ini diaktifkan dengan mengembalikan
true
, teks dan grafik dirender sesuai urutan z mereka dalam dokumen PDF asli.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Secara default, GroupDocs.Veiewer merender teks dan grafik sebagai satu lapisan dalam HTML. Opsi ini memungkinkan Anda mengatur objek dalam urutan yang sama seperti pada file sumber. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  jika rendering berlapis diaktifkan,  false  sebaliknya.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Mengaktifkan atau menonaktifkan perenderan teks dan grafik sesuai urutan z dalam dokumen PDF asli saat merender ke HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Secara default, GroupDocs.Veiewer merender teks dan grafik sebagai satu lapisan dalam HTML. Opsi ini memungkinkan Anda mengatur objek dalam urutan yang sama seperti pada file sumber. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  untuk mengaktifkan rendering berlapis,  false  untuk menonaktifkannya. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Menentukan apakah font hinting diaktifkan. Font hinting menyesuaikan tampilan font outline.
Opsi ini hanya didukung untuk font TrueType (TTF) ketika digunakan dalam dokumen sumber.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font hinting menyesuaikan cara font outline ditampilkan. Hanya berlaku untuk font TTF yang digunakan dalam dokumen sumber. Opsi ini tersedia untuk rendering ke format PNG atau JPG. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  jika font hinting diaktifkan,  false  sebaliknya.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Mengaktifkan font hinting. Font hinting menyesuaikan tampilan font outline dan hanya didukung untuk font TrueType (TTF) ketika digunakan dalam dokumen sumber.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font hinting menyesuaikan cara font outline ditampilkan. Hanya berlaku untuk font TTF yang digunakan dalam dokumen sumber. Opsi ini tersedia untuk rendering ke format PNG atau JPG. Nilai default adalah false.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | boolean | true  untuk mengaktifkan font hinting,  false  untuk menonaktifkannya. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Secara default, GroupDocs.Viewer menghitung ukuran halaman gambar output untuk kualitas rendering yang lebih baik. Aktifkan opsi ini untuk memastikan halaman output memiliki ukuran yang sama dengan ukuran halaman dokumen PDF sumber (dalam piksel). Nilai default adalah false.
Opsi ini tersedia untuk rendering ke format PNG atau JPG.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  jika opsi diaktifkan,  false  sebaliknya.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Secara default, GroupDocs.Viewer menghitung ukuran halaman gambar output untuk kualitas rendering yang lebih baik. Aktifkan opsi ini untuk memastikan halaman output memiliki ukuran yang sama dengan ukuran halaman dokumen PDF sumber (dalam piksel). Nilai default adalah false.
Opsi ini tersedia untuk rendering ke format PNG atau JPG.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true untuk mengaktifkan rendering dengan ukuran halaman asli, false jika tidak. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Mengambil kualitas gambar output untuk sumber daya gambar saat merender ke HTML. Nilai default adalah Low.


Ketika opsi ini diatur ke true, GroupDocs.Viewer merender teks sebagai gambar dalam output HTML. Ini membuat teks tidak dapat dipilih dan meningkatkan rendering karakter, memastikan tampilan seperti PDF dalam HTML. Nilai default adalah false.
Opsi ini tersedia untuk rendering ke HTML.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Mengatur kualitas gambar output untuk sumber daya gambar saat merender ke HTML. Nilai default adalah Low.


Ketika opsi ini diatur ke true, GroupDocs.Viewer merender teks sebagai gambar dalam output HTML. Ini membuat teks tidak dapat dipilih dan meningkatkan rendering karakter, memastikan tampilan seperti PDF dalam HTML. Nilai default adalah false.
Opsi ini tersedia untuk rendering ke HTML.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Kualitas gambar output untuk sumber daya gambar saat merender ke HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman.
Untuk memastikan bahwa HTML output terlihat sama dengan PDF sumber, dokumen dirender ke HTML dengan tata letak tetap secara default.
Saat merender dengan tata letak tetap, HTML output memiliki ukuran tetap sehingga elemen akan tetap pada posisi yang sama terlepas dari ukuran jendela.
Untuk merender ke HTML dengan tata letak cair, setel properti ini ke false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Dokumen PDF dan EPUB awalnya dirender ke HTML dengan tata letak tetap untuk mempertahankan tampilan dokumen sumber. Tata letak tetap ini berarti semua elemen HTML memiliki posisi yang tepat dalam sebuah kontainer dengan ukuran yang ditetapkan. Mengubah ukuran jendela browser tidak memengaruhi posisi dan ukuran elemen dalam dokumen.
Opsi ini hanya tersedia saat merender ke HTML. Nilai default adalah true. Untuk merender dengan tata letak cair, setel properti ini ke false.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true jika tata letak tetap

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman.
Untuk memastikan bahwa HTML output terlihat sama dengan PDF sumber, dokumen dirender ke HTML dengan tata letak tetap secara default.
Saat merender dengan tata letak tetap, HTML output memiliki ukuran tetap sehingga elemen akan tetap pada posisi yang sama terlepas dari ukuran jendela.
Untuk merender ke HTML dengan tata letak cair, setel properti ini ke false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Dokumen PDF dan EPUB awalnya dirender ke HTML dengan tata letak tetap untuk mempertahankan tampilan dokumen sumber. Tata letak tetap ini berarti semua elemen HTML memiliki posisi yang tepat dalam sebuah kontainer dengan ukuran yang ditetapkan. Mengubah ukuran jendela browser tidak memengaruhi posisi dan ukuran elemen dalam dokumen.
Opsi ini hanya tersedia saat merender ke HTML. Nilai default adalah true. Untuk merender dengan tata letak cair, setel properti ini ke false.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fixedLayout | boolean | true jika tata letak tetap |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG untuk meningkatkan kualitas output.


Opsi ini didukung saat merender [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) ke HTML dengan sumber daya tersemat dan eksternal.


Secara default, saat merender ke file PDF dan Page Layout, semua gambar dirender sebagai satu gambar PNG. Gambar PNG yang dirender digunakan sebagai latar belakang untuk dokumen HTML output.


Pelajari lebih lanjut:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean - true jika gambar dibungkus dalam SVG, false jika tidak.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG untuk meningkatkan kualitas output.


Opsi ini didukung saat merender [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) ke HTML dengan sumber daya tersemat dan eksternal.


Secara default, saat merender ke file PDF dan Page Layout, semua gambar dirender sebagai satu gambar PNG. Gambar PNG yang dirender digunakan sebagai latar belakang untuk dokumen HTML output.


Pelajari lebih lanjut:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true jika gambar harus dibungkus dalam SVG, false jika tidak. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | analyzeFonts | boolean | true jika font harus ditampilkan, false jika tidak. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini.


Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.
Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font ini.
Berhati-hatilah saat menggunakan flag ini. Ketika flag ini diatur, itu berarti bahwa orang yang mengatur flag ini mengambil semua tanggung jawab
atas kemungkinan pelanggaran lisensi/hukum pada diri mereka sendiri. Jadi mereka menanggung risikonya sendiri. Sangat disarankan untuk menggunakan
flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar undang-undang hak cipta. Secara default false.
Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Setel flag untuk menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini.


Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.
Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font ini.
Berhati-hatilah saat menggunakan flag ini. Ketika flag ini diatur, itu berarti bahwa orang yang mengatur flag ini mengambil semua tanggung jawab
atas kemungkinan pelanggaran lisensi/hukum pada diri mereka sendiri. Jadi mereka menanggung risikonya sendiri. Sangat disarankan untuk menggunakan
flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar undang-undang hak cipta. Secara default false.
Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

