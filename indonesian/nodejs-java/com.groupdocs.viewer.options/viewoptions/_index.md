---
title: "ViewOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Berisi opsi rendering."
type: docs
weight: 35
url: /id/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Berisi opsi rendering.

Kelas ViewOptions memperluas kelas BaseViewOptions dan berfungsi sebagai kelas dasar untuk opsi rendering dalam komponen GroupDocs.Viewer. Kelas ini mengenkapsulasi pengaturan dan parameter umum yang dapat digunakan untuk merender berbagai jenis dokumen ke dalam format yang berbeda.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWatermark()](#getWatermark--) | Mengambil watermark teks yang diterapkan pada setiap halaman. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Mengatur watermark teks yang akan diterapkan pada setiap halaman. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Menerapkan rotasi searah jarum jam pada halaman yang ditentukan. |
| [getPageRotations()](#getPageRotations--) | Mengambil rotasi halaman. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Untuk mencegah pembuatan instance hanya untuk memeriksa apakah itu kosong |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Mengambil watermark teks yang diterapkan pada setiap halaman.

Jika kedua \#setWatermark(Watermark).setWatermark(Watermark) dan \#getPageRotations().getPageRotations() ditentukan, watermark akan diterapkan pada halaman yang diputar. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Mengatur watermark teks yang akan diterapkan pada setiap halaman.

Jika kedua ViewOptions.Watermark dan \#getPageRotations().getPageRotations() ditentukan, watermark akan diterapkan pada halaman yang diputar. Untuk detail, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Watermark teks yang akan diatur. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Menerapkan rotasi searah jarum jam pada halaman yang ditentukan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | int | Nomor halaman harus lebih besar dari 0 secara ketat. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Nilai rotasi. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Mengambil rotasi halaman.

Jika kedua [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) dan getPageRotations() ditentukan, watermark akan diterapkan pada halaman yang diputar. Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - peta yang berisi nomor halaman sebagai kunci dan rotasi yang sesuai sebagai nilai.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Untuk mencegah pembuatan instance hanya untuk memeriksa apakah itu kosong

**Returns:**
boolean
