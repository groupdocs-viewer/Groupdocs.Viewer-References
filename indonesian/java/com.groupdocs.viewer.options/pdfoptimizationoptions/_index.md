---
title: "PdfOptimizationOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Gunakan kelas ini untuk menentukan opsi optimasi PDF yang akan diterapkan pada file PDF output."
type: docs
weight: 21
url: /id/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Gunakan kelas ini untuk menentukan opsi optimasi PDF yang akan diterapkan pada file PDF output.


Opsi optimasi ini didukung untuk semua format file masukan yang didukung untuk ekspor ke PDF.
Untuk detail dan contoh kode, lihat [halaman](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) ini dan turunannya.


Contoh penggunaan:

````

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
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Menetapkan nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Mengaktifkan optimasi file PDF output untuk dilihat secara online dengan peramban web. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Menetapkan apakah akan mengoptimasi PDF output untuk penelusuran online dengan peramban web. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Anotasi dapat dihapus ketika tidak diperlukan. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Menetapkan apakah akan menghapus anotasi yang tidak diperlukan dari PDF. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Jika dokumen PDF berisi AcroForms, kami dapat mencoba mengurangi ukuran file dengan meratakan bidang formulir. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Menetapkan apakah akan menghapus bidang formulir dari PDF. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | File PDF terdiri dari Teks, Gambar, Lampiran, Anotasi, Grafik, dan objek lainnya. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Menetapkan apakah akan mengonversi PDF ke skala abu-abu. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Setiap font yang digunakan untuk menampilkan teks pada halaman berisi kumpulan glif untuk karakter font. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Menetapkan apakah akan membuat subset font dalam PDF. |
|
|  | [isCompressImages()](#isCompressImages--) | Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Menetapkan apakah akan mengompresi gambar dalam PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Menetapkan kualitas gambar untuk mengompresi gambar dalam PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | Dapat digunakan bersama opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Mengatur apakah gambar dalam PDF harus diubah ukurannya. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Dapat digunakan bersama opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Mengatur resolusi maksimum untuk mengubah ukuran gambar dalam PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimalkan garis batas dan font pada spreadsheet Excel untuk ukuran file output yang lebih kecil. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Mengatur apakah spreadsheet dalam PDF harus dioptimalkan. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Hapus informasi pribadi (informasi potongan halaman) jika diatur ke true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Mengatur apakah informasi pribadi harus dihapus dari PDF. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Jika dokumen menggunakan font yang disematkan, itu berarti semua data font ditempatkan dalam dokumen. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Mengatur apakah font yang disematkan harus dilepaskan dari PDF. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Kadang-kadang sebuah dokumen berisi beberapa aliran sumber daya yang identik (misalnya gambar). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Mengatur apakah aliran duplikat harus ditautkan dalam PDF. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Jika properti ini diatur ke true, konten halaman akan digunakan kembali saat mengoptimalkan dokumen untuk halaman yang identik. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Mengatur apakah memperbolehkan penggunaan kembali konten halaman dalam PDF. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Kadang-kadang sebuah dokumen berisi aliran sumber daya yang tidak terpakai. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Mengatur apakah aliran yang tidak terpakai harus dihapus dari PDF. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Sebuah dokumen PDF kadang-kadang berisi objek PDF yang tidak direferensikan |
dari objek lain mana pun dalam dokumen.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Mengatur apakah objek yang tidak terpakai harus dihapus dari PDF. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Menetapkan nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100.


Untuk detail dan contoh kode, lihat [halaman](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) ini dan turunannya.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Mengaktifkan optimasi file PDF output untuk dilihat secara online dengan peramban web.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  jika PDF output dioptimalkan untuk penelusuran daring,  false  jika tidak.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Menetapkan apakah akan mengoptimasi PDF output untuk penelusuran online dengan peramban web.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | linearize | boolean | true  untuk mengoptimalkan PDF output untuk penelusuran daring,  false  jika tidak. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anotasi dapat dihapus ketika tidak diperlukan. Ketika diperlukan tetapi tidak memerlukan penyuntingan tambahan, anotasi dapat diratakan. Ini akan mengurangi ukuran file.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  jika anotasi dihapus,  false  jika tidak.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Menetapkan apakah akan menghapus anotasi yang tidak diperlukan dari PDF.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  untuk menghapus anotasi yang tidak diperlukan,  false  sebaliknya. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Jika dokumen PDF berisi AcroForms, kami dapat mencoba mengurangi ukuran file dengan meratakan bidang formulir.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  jika bidang formulir dihapus,  false  sebaliknya.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Menetapkan apakah akan menghapus bidang formulir dari PDF.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removeFormFields | boolean | true  untuk menghapus bidang formulir,  false  sebaliknya. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


File PDF terdiri dari Teks, Gambar, Lampiran, Anotasi, Grafik, dan objek lainnya.
Anda mungkin menemukan kebutuhan untuk mengonversi PDF dari ruang warna RGB ke skala abu-abu agar proses pencetakan file PDF tersebut menjadi lebih cepat.
Selain itu, ketika file dikonversi ke skala abu-abu, ukuran dokumen juga berkurang, namun dengan perubahan ini, kualitas dokumen dapat menurun.
Saat ini, fitur ini didukung oleh fitur Pre-Flight dari Adobe Acrobat.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  jika PDF dikonversi ke skala abu-abu,  false  sebaliknya.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Menetapkan apakah akan mengonversi PDF ke skala abu-abu.


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  untuk mengonversi PDF ke skala abu-abu,  false  sebaliknya. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Setiap font yang digunakan untuk menampilkan teks pada halaman berisi kumpulan glif untuk karakter font.
Spesifikasi PDF mendukung "font subset" yaitu font dengan hanya glif yang digunakan.
Hal ini dapat menyebabkan masalah ketika teks perlu diperbarui (karena kemungkinan glif yang diperlukan tidak ada dalam font), tetapi untuk dokumen yang tidak direncanakan diubah, ini memungkinkan mengurangi ukuran.


***Note:** The default value is 
false
.*
Jika file menggunakan font yang disematkan, ia berisi semua data font. GroupDocs.Viewer dapat melakukan subset pada font yang disematkan untuk mengurangi ukuran file. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  jika font disubset,  false  sebaliknya.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Menetapkan apakah akan membuat subset font dalam PDF.


***Note:** The default value is 
false
.*
Jika file menggunakan font yang disematkan, ia berisi semua data font. GroupDocs.Viewer dapat melakukan subset pada font yang disematkan untuk mengurangi ukuran file. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | subsetFonts | boolean | true  untuk melakukan subset pada font,  false  sebaliknya. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya.
Untuk mengaktifkan kompresi gambar, atur opsi ini ke true. Semua gambar dalam dokumen akan dikompresi ulang.
Kompresi didefinisikan oleh properti ImageQuality, yang merupakan nilai kualitas dalam persen.
100% berarti kualitas tidak berubah. Untuk menurunkan kualitas gambar, atur properti ImageQuality kurang dari 100.


***Note:** The default value is 
false
.*
Gunakan opsi ini untuk memungkinkan opsi kompresi lainnya: #setImageQuality(int).setImageQuality(int) dan . Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  jika gambar dikompresi,  false  sebaliknya.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Menetapkan apakah akan mengompresi gambar dalam PDF.


***Note:** The default value is 
false
.*
Gunakan opsi ini untuk memungkinkan opsi kompresi lainnya: #setImageQuality(int).setImageQuality(int) dan . Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | compressImages | boolean | true  untuk mengompresi gambar,  false  sebaliknya. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Jika file PDF sumber berisi gambar, pertimbangkan untuk mengompresi gambar dan mengatur kualitasnya. Untuk mengaktifkan kompresi gambar, setel opsi CompressImages ke true. Semua gambar dalam dokumen akan dikompresi ulang. Kompresi didefinisikan oleh properti ImageQuality, yang merupakan nilai kualitas dalam persen. 100% berarti kualitas tidak berubah. Untuk menurunkan kualitas gambar, setel opsi CompressImages ke true dan properti ImageQuality kurang dari 100.

<br />


***Note:** The default value is 
100
.*
Untuk mengubah kualitas gambar, pertama setel properti #setCompressImages(boolean).setCompressImages(boolean) ke true. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - kualitas gambar (nilai antara 1 dan 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Menetapkan kualitas gambar untuk mengompresi gambar dalam PDF.


***Note:** The default value is 
100
.*
Untuk mengubah kualitas gambar, pertama setel properti #setCompressImages(boolean).setCompressImages(boolean) ke true. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | imageQuality | int | kualitas gambar (nilai antara 1 dan 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Dapat digunakan bersama opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah.
Dalam kasus ini, kita harus menyetel CompressImage ke true, ResizeImages ke true, dan MaxResolution ke nilai yang sesuai.


***Note:** The default value is 
false
.*
Untuk mengizinkan opsi ini, setel properti ke true. Opsi ini memungkinkan pengaturan properti. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  jika gambar diubah ukurannya,  false  lainnya.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Mengatur apakah gambar dalam PDF harus diubah ukurannya.


***Note:** The default value is 
false
.*
Untuk mengizinkan opsi ini, setel properti ke true. Opsi ini memungkinkan pengaturan properti. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | resizeImages | boolean | true  untuk mengubah ukuran gambar,  false  lainnya. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Dapat digunakan dengan opsi CompressImages untuk mengubah ukuran gambar dengan resolusi lebih rendah. Dalam kasus ini, kita harus menyetel CompressImage ke true, ResizeImages ke true, dan MaxResolution ke nilai yang sesuai.


***Note:** The default value is 
300
.*
Untuk mengizinkan opsi ini, setel properti #setCompressImages(boolean).setCompressImages(boolean) dan #setMaxResolution(int).setMaxResolution(int) ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - resolusi maksimum untuk gambar.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Mengatur resolusi maksimum untuk mengubah ukuran gambar dalam PDF.


***Note:** The default value is 
300
.*
Untuk mengizinkan opsi ini, setel properti #setCompressImages(boolean).setCompressImages(boolean) dan #setMaxResolution(int).setMaxResolution(int) ke true.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxResolution | int | resolusi maksimum untuk gambar. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimalkan garis batas dan font pada spreadsheet Excel untuk ukuran file output yang lebih kecil.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  jika spreadsheet dioptimalkan,  false  lainnya.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Mengatur apakah spreadsheet dalam PDF harus dioptimalkan.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  untuk mengoptimalkan spreadsheet,  false  lainnya. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Hapus informasi pribadi (informasi potongan halaman) jika diatur ke true.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika informasi pribadi dihapus,  false  lainnya.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Mengatur apakah informasi pribadi harus dihapus dari PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  untuk menghapus informasi pribadi,  false  lainnya. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Jika dokumen menggunakan font yang disematkan, itu berarti semua data font ditempatkan dalam dokumen.
Keuntungannya adalah dokumen dapat dilihat terlepas dari apakah font terpasang di mesin pengguna\u2019s atau tidak. Namun menyematkan font membuat dokumen menjadi lebih besar.
Metode unembed fonts menghapus semua font yang disematkan. Ini mengurangi ukuran dokumen tetapi dokumen dapat menjadi tidak dapat dibaca jika font yang tepat tidak terpasang.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika font yang disematkan telah di-unembed,  false  sebaliknya.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Mengatur apakah font yang disematkan harus dilepaskan dari PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | unembedFonts | boolean | true  untuk meng-unembed font yang disematkan,  false  sebaliknya. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Kadang-kadang sebuah dokumen berisi beberapa aliran sumber daya yang identik (misalnya gambar).
Ini dapat terjadi misalnya ketika sebuah dokumen digabungkan dengan dirinya sendiri.
Dokumen output berisi dua salinan independen dari aliran sumber daya yang sama.
Kami menganalisis semua aliran sumber daya dan membandingkannya. Jika aliran duplikat, mereka digabungkan, yaitu hanya satu salinan yang tersisa, referensi diubah secara tepat dan salinan objek dihapus.
Kadang-kadang ini mengurangi ukuran dokumen.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika aliran duplikat ditautkan,  false  sebaliknya.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Mengatur apakah aliran duplikat harus ditautkan dalam PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  untuk menautkan aliran duplikat,  false  sebaliknya. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Jika properti ini diatur ke true, konten halaman akan digunakan kembali saat mengoptimalkan dokumen untuk halaman yang identik.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika konten halaman digunakan kembali,  false  sebaliknya.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Mengatur apakah memperbolehkan penggunaan kembali konten halaman dalam PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  untuk mengizinkan penggunaan kembali konten halaman,  false  sebaliknya. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Kadang-kadang sebuah dokumen berisi aliran sumber daya yang tidak terpakai.
Aliran ini bukan \u201cunused objects\u201d karena mereka direferensikan dari kamus sumber daya halaman\u2019s.
Ini dapat terjadi dalam kasus di mana sebuah gambar telah dihapus dari halaman tetapi tidak dari sumber daya halaman.
Juga, situasi ini sering terjadi ketika halaman diekstrak dari dokumen dan halaman dokumen memiliki sumber daya \u201ccommon\u201d,
yaitu, objek Resources yang sama. Konten halaman dianalisis untuk menentukan apakah aliran sumber daya
digunakan atau tidak. Aliran yang tidak digunakan dihapus. Kadang-kadang ini mengurangi ukuran dokumen.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika aliran yang tidak digunakan dihapus,  false  sebaliknya.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Mengatur apakah aliran yang tidak terpakai harus dihapus dari PDF.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  untuk menghapus aliran yang tidak digunakan,  false  sebaliknya. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Sebuah dokumen PDF kadang-kadang berisi objek PDF yang tidak direferensikan
dari objek lain apa pun dalam dokumen. Ini dapat terjadi, misalnya,
ketika sebuah halaman dihapus dari pohon halaman dokumen tetapi objek halaman itu sendiri isn\u2019t dihapus.
Menghapus objek-objek ini tidak membuat dokumen tidak valid tetapi justru memperkecilnya.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  jika objek yang tidak terpakai dihapus,  false  jika tidak.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Mengatur apakah objek yang tidak terpakai harus dihapus dari PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  untuk menghapus objek yang tidak terpakai,  false  jika tidak. |
|

