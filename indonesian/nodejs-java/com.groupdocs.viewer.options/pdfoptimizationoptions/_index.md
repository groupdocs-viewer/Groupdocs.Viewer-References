---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Gunakan kelas ini untuk menentukan opsi optimasi PDF yang akan diterapkan pada file PDF keluaran."
type: docs
weight: 21
url: /id/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Gunakan kelas ini untuk menentukan opsi optimasi PDF yang akan diterapkan pada file PDF keluaran.

Opsi optimasi ini didukung untuk semua format file input yang didukung untuk ekspor ke PDF. Untuk detail dan contoh kode, lihat [page][] dan turunannya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Menetapkan nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isLinearize()](#isLinearize--) | Mengaktifkan optimasi file PDF output untuk dilihat secara online dengan peramban web. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Mengatur apakah akan mengoptimasi PDF output untuk penelusuran online dengan peramban web. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Anotasi dapat dihapus ketika tidak diperlukan. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Mengatur apakah akan menghapus anotasi yang tidak diperlukan dari PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Jika dokumen PDF berisi AcroForms, kita dapat mencoba mengurangi ukuran file dengan meratakan bidang formulir. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Mengatur apakah akan menghapus bidang formulir dari PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | File PDF terdiri dari Teks, Gambar, Lampiran, Anotasi, Grafik, dan objek lainnya. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Mengatur apakah akan mengonversi PDF ke skala abu-abu. |
| [isSubsetFonts()](#isSubsetFonts--) | Setiap font yang digunakan untuk menampilkan teks pada halaman berisi kumpulan glif untuk karakter font. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Mengatur apakah akan membuat subset font dalam PDF. |
| [isCompressImages()](#isCompressImages--) | Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompres gambar dan mengatur kualitasnya. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Mengatur apakah akan mengompres gambar dalam PDF. |
| [getImageQuality()](#getImageQuality--) | Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompres gambar dan mengatur kualitasnya. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Mengatur kualitas gambar untuk mengompres gambar dalam PDF. |
| [isResizeImages()](#isResizeImages--) | Dapat digunakan bersama opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Mengatur apakah akan mengubah ukuran gambar dalam PDF. |
| [getMaxResolution()](#getMaxResolution--) | Dapat digunakan bersama opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Mengatur resolusi maksimum untuk mengubah ukuran gambar dalam PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimalkan garis batas dan font spreadsheet Excel untuk ukuran file output yang lebih kecil. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Mengatur apakah akan mengoptimalkan spreadsheet dalam PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Hapus informasi pribadi (informasi potongan halaman) jika diatur ke true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Mengatur apakah akan menghapus informasi pribadi dari PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | Jika dokumen menggunakan font tertanam, itu berarti semua data font ditempatkan dalam dokumen. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Mengatur apakah akan mengeluarkan font tertanam dari PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Kadang-kadang sebuah dokumen berisi beberapa aliran sumber daya yang identik (misalnya gambar). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Mengatur apakah akan menautkan aliran duplikat dalam PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Jika properti ini diatur ke true, konten halaman akan digunakan kembali saat mengoptimalkan dokumen untuk halaman yang identik. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Mengatur apakah mengizinkan penggunaan kembali konten halaman dalam PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Kadang-kadang dokumen berisi aliran sumber daya yang tidak terpakai. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Mengatur apakah menghapus aliran yang tidak terpakai dari PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Dokumen PDF kadang-kadang berisi objek PDF yang tidak direferensikan oleh objek lain dalam dokumen. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Mengatur apakah menghapus objek yang tidak terpakai dari PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Menetapkan nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100.

Untuk detail dan contoh kode, lihat [page][] ini dan turunannya.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Mengaktifkan optimasi file PDF output untuk dilihat secara online dengan peramban web.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  jika PDF output dioptimalkan untuk penelusuran daring,  false  jika tidak.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Mengatur apakah akan mengoptimasi PDF output untuk penelusuran online dengan peramban web.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linearize | boolean | true  untuk mengoptimalkan PDF output untuk penelusuran daring,  false  jika tidak. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anotasi dapat dihapus ketika tidak diperlukan. Ketika diperlukan tetapi tidak memerlukan penyuntingan tambahan, anotasi dapat dilapiskan. Ini akan mengurangi ukuran file.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  jika anotasi dihapus,  false  jika tidak.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Mengatur apakah akan menghapus anotasi yang tidak diperlukan dari PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeAnnotations | boolean | true  untuk menghapus anotasi yang tidak diperlukan,  false  jika tidak. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Jika dokumen PDF berisi AcroForms, kita dapat mencoba mengurangi ukuran file dengan meratakan bidang formulir.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  jika bidang formulir dihapus,  false  jika tidak.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Mengatur apakah akan menghapus bidang formulir dari PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeFormFields | boolean | true  untuk menghapus bidang formulir,  false  jika tidak. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


File PDF terdiri dari Teks, Gambar, Lampiran, Anotasi, Grafik, dan objek lainnya. Anda mungkin menemukan kebutuhan untuk mengonversi PDF dari ruang warna RGB ke skala abu-abu agar proses pencetakan file PDF tersebut menjadi lebih cepat. Selain itu, ketika file dikonversi ke skala abu-abu, ukuran dokumen juga berkurang, namun dengan perubahan ini, kualitas dokumen dapat menurun. Saat ini, fitur ini didukung oleh fitur Pre-Flight pada Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  jika PDF dikonversi ke skala abu-abu,  false  jika tidak.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Mengatur apakah akan mengonversi PDF ke skala abu-abu.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertToGrayScale | boolean | true  untuk mengonversi PDF ke skala abu-abu,  false  jika tidak. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Setiap font yang digunakan untuk menampilkan teks pada halaman berisi sekumpulan glif untuk karakter font. Spesifikasi PDF mendukung "font subset", yaitu font yang hanya memiliki glif yang digunakan. Hal ini dapat menimbulkan masalah ketika teks perlu diperbarui (karena kemungkinan glif yang diperlukan tidak ada dalam font), tetapi untuk dokumen yang tidak direncanakan diubah, hal ini memungkinkan pengurangan ukuran.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  jika font disubset,  false  jika tidak.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Mengatur apakah akan membuat subset font dalam PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| subsetFonts | boolean | true  untuk melakukan subset pada font,  false  jika tidak. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya. Untuk mengaktifkan kompresi gambar, setel opsi ini ke true. Semua gambar dalam dokumen akan dikompresi ulang. Kompresi didefinisikan oleh properti ImageQuality, yang merupakan nilai kualitas dalam persen. 100% adalah kualitas yang tidak berubah. Untuk menurunkan kualitas gambar, setel properti ImageQuality kurang dari 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  jika gambar dikompresi,  false  jika tidak.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Mengatur apakah akan mengompres gambar dalam PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| compressImages | boolean | true  untuk mengompresi gambar,  false  jika tidak. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya. Untuk mengaktifkan kompresi gambar, setel opsi CompressImages ke true. Semua gambar dalam dokumen akan dikompresi ulang. Kompresi didefinisikan oleh properti ImageQuality, yang merupakan nilai kualitas dalam persen. 100% adalah kualitas yang tidak berubah. Untuk menurunkan kualitas gambar, setel opsi CompressImages ke true dan properti ImageQuality kurang dari 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - kualitas gambar (nilai antara 1 dan 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Mengatur kualitas gambar untuk mengompres gambar dalam PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageQuality | int | kualitas gambar (nilai antara 1 dan 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Dapat digunakan dengan opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. Dalam kasus ini, kita harus setel CompressImage ke true, ResizeImages ke true, dan MaxResolution ke nilai yang sesuai.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  jika gambar diubah ukurannya,  false  jika tidak.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Mengatur apakah akan mengubah ukuran gambar dalam PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resizeImages | boolean | true  untuk mengubah ukuran gambar,  false  jika tidak. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Dapat digunakan dengan opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. Dalam kasus ini, kita harus setel CompressImage ke true, ResizeImages ke true, dan MaxResolution ke nilai yang sesuai.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - resolusi maksimum untuk gambar.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Mengatur resolusi maksimum untuk mengubah ukuran gambar dalam PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxResolution | int | resolusi maksimum untuk gambar. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimalkan garis batas dan font spreadsheet Excel untuk ukuran file output yang lebih kecil.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  jika spreadsheet dioptimalkan,  false  jika tidak.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Mengatur apakah akan mengoptimalkan spreadsheet dalam PDF.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  untuk mengoptimalkan spreadsheet,  false  jika tidak. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Hapus informasi pribadi (informasi potongan halaman) jika diatur ke true.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika informasi pribadi dihapus,  false  jika tidak.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Mengatur apakah akan menghapus informasi pribadi dari PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removePrivateInfo | boolean | true  untuk menghapus informasi pribadi,  false  jika tidak. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Jika dokumen menggunakan font yang disematkan, itu berarti semua data font ditempatkan dalam dokumen. Keuntungannya adalah dokumen dapat dilihat terlepas dari apakah font tersebut terpasang di mesin pengguna atau tidak. Namun, menyematkan font membuat dokumen menjadi lebih besar. Metode unembed fonts menghapus semua font yang disematkan. Ini mengurangi ukuran dokumen tetapi dokumen mungkin menjadi tidak dapat dibaca jika font yang tepat tidak terpasang.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika font yang disematkan di-unembed,  false  jika tidak.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Mengatur apakah akan mengeluarkan font tertanam dari PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| unembedFonts | boolean | true  untuk meng-unembed font yang disematkan,  false  jika tidak. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Kadang sebuah dokumen berisi beberapa aliran sumber daya yang identik (misalnya gambar). Hal ini dapat terjadi, misalnya ketika sebuah dokumen digabungkan dengan dirinya sendiri. Dokumen output berisi dua salinan independen dari aliran sumber daya yang sama. Kami menganalisis semua aliran sumber daya dan membandingkannya. Jika aliran duplikat, mereka digabungkan, yaitu hanya satu salinan yang tersisa, referensi diubah secara tepat dan salinan objek dihapus. Kadang hal ini mengurangi ukuran dokumen.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika aliran duplikat ditautkan,  false  jika tidak.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Mengatur apakah akan menautkan aliran duplikat dalam PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  untuk menautkan aliran duplikat,  false  jika tidak. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Jika properti ini diatur ke true, konten halaman akan digunakan kembali saat mengoptimalkan dokumen untuk halaman yang identik.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika konten halaman digunakan kembali,  false  jika tidak.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Mengatur apakah mengizinkan penggunaan kembali konten halaman dalam PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowReusePageContent | boolean | true  untuk mengizinkan penggunaan kembali konten halaman,  false  jika tidak. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Kadang sebuah dokumen berisi aliran sumber daya yang tidak terpakai. Aliran ini bukan \u201cunused objects\u201d karena mereka dirujuk dari kamus sumber daya halaman. Hal ini dapat terjadi dalam kasus di mana sebuah gambar telah dihapus dari halaman tetapi tidak dari sumber daya halaman. Juga, situasi ini sering terjadi ketika halaman diekstrak dari dokumen dan halaman dokumen memiliki sumber daya \u201ccommon\u201d, yaitu objek Resources yang sama. Konten halaman dianalisis untuk menentukan apakah aliran sumber daya digunakan atau tidak. Aliran yang tidak terpakai dihapus. Kadang hal ini mengurangi ukuran dokumen.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika aliran yang tidak terpakai dihapus,  false  jika tidak.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Mengatur apakah menghapus aliran yang tidak terpakai dari PDF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  untuk menghapus aliran yang tidak terpakai,  false  jika tidak. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Sebuah dokumen PDF kadang berisi objek PDF yang tidak dirujuk dari objek lain mana pun dalam dokumen. Hal ini dapat terjadi, misalnya, ketika sebuah halaman dihapus dari pohon halaman dokumen tetapi objek halaman itu sendiri tidak dihapus. Menghapus objek-objek ini tidak membuat dokumen menjadi tidak valid tetapi justru memperkecilnya.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  jika objek yang tidak terpakai dihapus,  false  jika tidak.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Mengatur apakah menghapus objek yang tidak terpakai dari PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  untuk menghapus objek yang tidak terpakai,  false  jika tidak. |

