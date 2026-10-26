---
title: "PdfOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender dokumen PDF."
type: docs
weight: 22
url: /id/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Menyediakan opsi untuk merender dokumen PDF.

Kelas PdfOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk mengontrol perenderan dokumen PDF dalam komponen GroupDocs.Viewer. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Menginisialisasi instance baru dari kelas PdfOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Menonaktifkan perlindungan penyalinan konten saat merender ke HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Menonaktifkan perlindungan penyalinan konten saat merender ke HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Menentukan apakah teks dari sumber dirender sebagai gambar dalam HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Mengatur apakah teks dari sumber dirender sebagai gambar dalam HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Memeriksa apakah pengelompokan karakter dinonaktifkan untuk mempertahankan presisi maksimum selama penempatan karakter saat merender halaman. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Mengatur opsi untuk menonaktifkan pengelompokan karakter, memastikan presisi maksimum selama penempatan karakter saat merender halaman. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Memeriksa apakah perenderan teks dan grafik harus mengikuti urutan z dalam dokumen PDF asli saat merender ke HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Mengaktifkan atau menonaktifkan perenderan teks dan grafik sesuai urutan z dalam dokumen PDF asli saat merender ke HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Menentukan apakah hinting font diaktifkan. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Mengaktifkan hinting font. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber. |
| [getImageQuality()](#getImageQuality--) | Mengambil kualitas gambar output untuk sumber daya gambar saat merender ke HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Mengatur kualitas gambar output untuk sumber daya gambar saat merender ke HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF adalah format tetap sehingga semua elemen memiliki tempat tertentu pada halaman. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF adalah format tetap sehingga semua elemen memiliki tempat tertentu pada halaman. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG guna meningkatkan kualitas output. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG guna meningkatkan kualitas output. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Mencoba memperbaiki masalah ketika seluruh konten halaman HTML merupakan tautan. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Mencoba memperbaiki masalah ketika seluruh konten halaman HTML merupakan tautan. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Atur flag untuk menonaktifkan semua pembatasan lisensi pada semua font dalam dokumen XPS/OXPS saat ini. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Menginisialisasi instance baru dari kelas PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Menonaktifkan perlindungan penyalinan konten saat merender ke HTML.

Saat merender file PDF dengan perlindungan terhadap penyalinan teks dan gambar ke HTML, GroupDocs.Viewer menambahkan atribut HTML 'inert' ke tag HTML BODY. Nilai default opsi ini adalah false.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Menonaktifkan perlindungan penyalinan konten saat merender ke HTML.

Saat merender file PDF dengan perlindungan terhadap penyalinan teks dan gambar ke HTML, GroupDocs.Viewer menambahkan atribut HTML 'inert' ke tag HTML BODY. Nilai default opsi ini adalah false.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Menentukan apakah teks dari sumber dirender sebagai gambar dalam HTML.

Ketika opsi ini diatur ke true, teks dirender sebagai gambar dalam HTML output. Aktifkan opsi ini untuk membuat teks tidak dapat dipilih atau untuk memperbaiki perenderan karakter dan membuat HTML terlihat seperti PDF. Opsi ini didukung saat merender ke HTML.

***Note:** The default value is  false .*

**Returns:**
boolean - true jika teks dirender sebagai gambar dalam HTML, false jika tidak.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Mengatur apakah teks dari sumber dirender sebagai gambar dalam HTML.

Ketika opsi ini diatur ke true, teks dirender sebagai gambar dalam HTML output. Aktifkan opsi ini untuk membuat teks tidak dapat dipilih atau untuk memperbaiki perenderan karakter dan membuat HTML terlihat seperti PDF. Opsi ini didukung saat merender ke HTML.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderTextAsImage | boolean | true untuk merender teks sebagai gambar dalam HTML, false jika tidak. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Memeriksa apakah pengelompokan karakter dinonaktifkan untuk mempertahankan presisi maksimum selama penempatan karakter saat merender halaman. Ketika opsi ini diaktifkan, karakter dirender tanpa pengelompokan apa pun, yang memastikan presisi maksimum.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - true jika pengelompokan karakter dinonaktifkan, false jika tidak.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Mengatur opsi untuk menonaktifkan pengelompokan karakter, memastikan presisi maksimum selama penempatan karakter saat merender halaman. Ketika opsi ini diaktifkan dengan mengatur nilai ke true, pengelompokan karakter dinonaktifkan, yang memastikan presisi maksimum.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true untuk menonaktifkan pengelompokan karakter, false untuk mengaktifkannya. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Memeriksa apakah perenderan teks dan grafik harus mengikuti urutan z dalam dokumen PDF asli saat merender ke HTML. Ketika opsi ini diaktifkan dengan mengembalikan true, teks dan grafik dirender sesuai urutan z mereka dalam dokumen PDF asli.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - true jika perenderan berlapis diaktifkan, false jika tidak.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Mengaktifkan atau menonaktifkan perenderan teks dan grafik sesuai urutan z dalam dokumen PDF asli saat merender ke HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true untuk mengaktifkan perenderan berlapis, false untuk menonaktifkannya. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Menentukan apakah hinting font diaktifkan. Hinting font menyesuaikan tampilan font outline. Opsi ini hanya didukung untuk font TrueType (TTF) ketika digunakan dalam dokumen sumber.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - true jika hinting font diaktifkan, false jika tidak.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Mengaktifkan hinting font. Hinting font menyesuaikan tampilan font outline dan hanya didukung untuk font TrueType (TTF) ketika digunakan dalam dokumen sumber.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true untuk mengaktifkan hinting font, false untuk menonaktifkannya. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - true jika opsi diaktifkan, false jika tidak.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Mengaktifkan perenderan halaman dengan ukuran piksel yang sama dengan ukuran halaman dalam dokumen PDF sumber.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true untuk mengaktifkan perenderan dengan ukuran halaman asli, false jika tidak. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Mengambil kualitas gambar output untuk sumber daya gambar saat merender ke HTML. Nilai default adalah Low.

Ketika opsi ini diatur ke true, GroupDocs.Viewer merender teks sebagai gambar dalam output HTML. Ini membuat teks tidak dapat dipilih dan meningkatkan perenderan karakter, memastikan tampilan seperti PDF dalam HTML. Nilai default adalah false. Opsi ini tersedia untuk perenderan ke HTML. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Mengatur kualitas gambar output untuk sumber daya gambar saat merender ke HTML. Nilai default adalah Low.

Ketika opsi ini diatur ke true, GroupDocs.Viewer merender teks sebagai gambar dalam output HTML. Ini membuat teks tidak dapat dipilih dan meningkatkan perenderan karakter, memastikan tampilan seperti PDF dalam HTML. Nilai default adalah false. Opsi ini tersedia untuk perenderan ke HTML. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Kualitas gambar output untuk sumber gambar saat merender ke HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman. Untuk memastikan bahwa HTML output terlihat sama dengan PDF sumber, dokumen dirender ke HTML dengan tata letak tetap secara default. Saat merender dengan tata letak tetap, HTML output memiliki ukuran tetap sehingga elemen akan tetap pada posisi yang sama terlepas dari ukuran jendela. Untuk merender ke HTML dengan tata letak cair, set properti ini ke false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true jika menggunakan tata letak tetap
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF adalah format tetap sehingga semua elemen memiliki posisi tertentu pada halaman. Untuk memastikan bahwa HTML output terlihat sama dengan PDF sumber, dokumen dirender ke HTML dengan tata letak tetap secara default. Saat merender dengan tata letak tetap, HTML output memiliki ukuran tetap sehingga elemen akan tetap pada posisi yang sama terlepas dari ukuran jendela. Untuk merender ke HTML dengan tata letak cair, set properti ini ke false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixedLayout | boolean | true jika menggunakan tata letak tetap |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG guna meningkatkan kualitas output.

Opsi ini didukung saat merender [PDF and Page Layout file formats][] ke HTML dengan sumber daya tersemat dan eksternal.

Secara default, saat merender ke file PDF dan Page Layout, semua gambar dirender sebagai satu gambar PNG. Gambar PNG yang dirender digunakan sebagai latar belakang untuk dokumen HTML output.

Pelajari lebih lanjut:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  jika gambar dibungkus dalam SVG,  false  sebaliknya.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktifkan opsi ini untuk membungkus setiap gambar dalam dokumen HTML output dengan tag SVG guna meningkatkan kualitas output.

Opsi ini didukung saat merender [PDF and Page Layout file formats][] ke HTML dengan sumber daya tersemat dan eksternal.

Secara default, saat merender ke file PDF dan Page Layout, semua gambar dirender sebagai satu gambar PNG. Gambar PNG yang dirender digunakan sebagai latar belakang untuk dokumen HTML output.

Pelajari lebih lanjut:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  jika gambar harus dibungkus dalam SVG,  false  sebaliknya. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Mencoba memperbaiki masalah ketika seluruh konten halaman HTML adalah tautan. Hanya berfungsi ketika format input adalah PDF dan format output adalah HTML (dengan sumber daya tersemat atau eksternal). Secara default dinonaktifkan (false). Aktifkan hanya ketika Anda tahu apa dan mengapa Anda melakukannya. Mengaktifkan opsi ini meningkatkan waktu pemrosesan dokumen.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Mencoba memperbaiki masalah ketika seluruh konten halaman HTML adalah tautan. Hanya berfungsi ketika format input adalah PDF dan format output adalah HTML (dengan sumber daya tersemat atau eksternal). Secara default dinonaktifkan (false). Aktifkan hanya ketika Anda tahu apa dan mengapa Anda melakukannya. Mengaktifkan opsi ini meningkatkan waktu pemrosesan dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixLinkIssue | boolean | true jika masalah harus diperbaiki, false sebaliknya. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Mengganti font sesuai kebutuhan untuk memastikan semua karakter dalam teks dapat ditampilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| analyzeFonts | boolean | true jika font harus ditampilkan, false sebaliknya. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini.

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font tersebut. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum pada dirinya sendiri. Jadi mereka menanggung risikonya sendiri. Sangat disarankan menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hak cipta. Secara default false. Untuk contoh kode, lihat [documentation][].

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Atur flag untuk menonaktifkan semua pembatasan lisensi pada semua font dalam dokumen XPS/OXPS saat ini.

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font tersebut. Hati-hati saat menggunakan flag ini. Ketika diatur, berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum pada dirinya sendiri. Jadi mereka menanggung risikonya sendiri. Sangat disarankan menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hak cipta. Secara default false. Untuk contoh kode, lihat [documentation][].

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

