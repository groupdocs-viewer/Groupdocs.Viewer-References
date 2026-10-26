---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender dokumen ke format HTML."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Menyediakan opsi untuk merender dokumen ke format HTML.

Kelas HtmlViewOptions mengenkapsulasi pengaturan dan parameter tambahan yang dapat digunakan untuk mengontrol rendering dokumen ke format HTML dalam komponen GroupDocs.Viewer.

Untuk detail, lihat [topic][] dan anaknya.

Contoh penggunaan:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Menentukan apakah rendering responsif diaktifkan. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Mengatur apakah rendering responsif diaktifkan. |
| [isMinify()](#isMinify--) | Memeriksa apakah minifikasi konten HTML dan sumber daya HTML diaktifkan. |
| [setMinify(boolean value)](#setMinify-boolean-) | Mengatur apakah minifikasi konten HTML dan sumber daya HTML diaktifkan. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Mengaktifkan rendering seluruh dokumen menjadi satu file HTML. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Mengaktifkan rendering seluruh dokumen menjadi satu file HTML. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Mengembalikan lebar maksimum gambar output dalam piksel. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Mengatur lebar maksimum gambar output dalam piksel. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Mendapatkan tinggi maksimum gambar output dalam piksel. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Mengatur tinggi maksimum gambar output dalam piksel. |
| [getImageWidth()](#getImageWidth--) | Mendapatkan lebar gambar output dalam piksel. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Mengatur lebar gambar output dalam piksel. |
| [getImageHeight()](#getImageHeight--) | Mendapatkan tinggi gambar output dalam piksel saat mengonversi satu gambar ke HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Mengatur tinggi gambar output dalam piksel saat mengonversi satu gambar ke HTML. |
| [isForPrinting()](#isForPrinting--) | Memeriksa apakah HTML output harus dioptimalkan untuk pencetakan. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Mengatur apakah HTML output harus dioptimalkan untuk pencetakan. |
| [isExcludeFonts()](#isExcludeFonts--) | Menentukan apakah akan mengecualikan font dari dokumen HTML. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Mengatur apakah akan mengecualikan font dari dokumen HTML. |
| [getFontsToExclude()](#getFontsToExclude--) | Mengambil daftar nama font yang akan dikecualikan dari dokumen HTML. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Mengatur daftar nama font yang akan dikecualikan dari dokumen HTML. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Mengizinkan penghapusan kode sumber JavaScript dari tautan dalam dokumen HTML yang dihasilkan, saat merender dokumen masukan yang memiliki skrip. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Mengatur izin untuk menghapus kode sumber JavaScript dari tautan dalam dokumen HTML yang dihasilkan, saat merender dokumen masukan yang memiliki skrip. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Mengambil callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Mengatur callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Menginisialisasi instance baru dari kelas  HtmlViewOptions . |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions . |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions . |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal. |
| [forExternalResources()](#forExternalResources--) | Menginisialisasi instance baru dari kelas  HtmlViewOptions . |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas  HtmlViewOptions . |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Menentukan apakah rendering responsif diaktifkan. Halaman web responsif merender dengan baik pada perangkat dengan ukuran layar yang berbeda.

Desain responsif bertujuan agar halaman web merender dengan baik pada berbagai perangkat. Untuk merender dengan tata letak responsif, atur properti ini ke true. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolean -  true  jika rendering responsif diaktifkan,  false  sebaliknya.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Mengatur apakah rendering responsif diaktifkan. Halaman web responsif merender dengan baik pada perangkat dengan ukuran layar yang berbeda.

Desain responsif bertujuan agar halaman web merender dengan baik pada berbagai perangkat. Untuk merender dengan tata letak responsif, atur properti ini ke true. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan rendering responsif,  false  untuk menonaktifkannya. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Memeriksa apakah minifikasi konten HTML dan sumber daya HTML diaktifkan.

Kompressi konten output (HTML, CSS, dan SVG) adalah salah satu cara untuk mengoptimalkan file HTML. Untuk melakukannya, atur properti ini ke true. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  jika minifikasi diaktifkan,  false  sebaliknya.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Mengatur apakah minifikasi konten HTML dan sumber daya HTML diaktifkan.

Kompressi konten output (HTML, CSS, dan SVG) adalah salah satu cara untuk mengoptimalkan file HTML. Untuk melakukannya, atur properti ini ke true. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengaktifkan minifikasi,  false  untuk menonaktifkannya. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Mengaktifkan rendering seluruh dokumen menjadi satu file HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Mengaktifkan rendering seluruh dokumen menjadi satu file HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Mengembalikan lebar maksimum gambar output dalam piksel.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - lebar maksimum gambar output.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Mengatur lebar maksimum gambar output dalam piksel.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageMaxWidth | int | Lebar maksimum gambar output. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Mendapatkan tinggi maksimum gambar output dalam piksel.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - tinggi maksimum gambar output.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Mengatur tinggi maksimum gambar output dalam piksel.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageMaxHeight | int | Tinggi maksimum gambar output. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Mendapatkan lebar gambar output dalam piksel.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - lebar gambar output.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Mengatur lebar gambar output dalam piksel.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageWidth | int | Lebar gambar output. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Mendapatkan tinggi gambar output dalam piksel saat mengonversi satu gambar ke HTML.

Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - tinggi gambar output dalam piksel.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Mengatur tinggi gambar output dalam piksel saat mengonversi satu gambar ke HTML.

Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageHeight | int | Tinggi gambar output dalam piksel. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Memeriksa apakah HTML output harus dioptimalkan untuk pencetakan.

Aktifkan opsi ini untuk mengonversi halaman HTML output ke format vektor SVG. Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  jika HTML output harus dioptimalkan untuk pencetakan,  false  sebaliknya.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Mengatur apakah HTML output harus dioptimalkan untuk pencetakan.

Aktifkan opsi ini untuk mengonversi halaman HTML output ke format vektor SVG. Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengoptimalkan HTML output untuk pencetakan,  false  sebaliknya. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Menentukan apakah akan mengecualikan font dari dokumen HTML.

Secara default, GroupDocs.Viewer menyematkan font yang digunakan dalam dokumen ke dalam HTML. Untuk mencegahnya, setel properti ini ke true. Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  jika font harus dikecualikan,  false  sebaliknya.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Mengatur apakah akan mengecualikan font dari dokumen HTML.

Secara default, GroupDocs.Viewer menyematkan font yang digunakan dalam dokumen ke dalam HTML. Untuk mencegahnya, setel properti ini ke true. Untuk detail dan contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean | true  untuk mengecualikan font,  false  sebaliknya. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Mengambil daftar nama font yang akan dikecualikan dari dokumen HTML.

Opsi ini hanya didukung untuk presentasi. Menyertakan font dalam dokumen HTML meningkatkan stabilitas tampilan output tetapi meningkatkan ukuran hasil render. Gunakan opsi ini untuk menemukan kompromi antara stabilitas dan ukuran output. Sertakan nama font yang populer dan terpasang pada kebanyakan sistem.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - daftar nama font yang akan dikecualikan dari dokumen HTML.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Mengatur daftar nama font yang akan dikecualikan dari dokumen HTML.

Opsi ini hanya didukung untuk presentasi. Menyertakan font dalam dokumen HTML meningkatkan stabilitas tampilan output tetapi meningkatkan ukuran hasil render. Gunakan opsi ini untuk menemukan kompromi antara stabilitas dan ukuran output. Sertakan nama font yang populer dan terpasang pada kebanyakan sistem.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | Daftar nama font yang akan dikecualikan dari dokumen HTML. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Mengizinkan penghapusan kode sumber JavaScript dari tautan dalam dokumen HTML hasil, saat merender dokumen input yang memiliki skrip. Secara default diaktifkan (true).

Untuk detail tentang penghapusan JavaScript, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Mengatur izin untuk menghapus kode sumber JavaScript dari tautan dalam dokumen HTML hasil, saat merender dokumen input yang memiliki skrip. Secara default diaktifkan (true).

Untuk detail tentang penghapusan JavaScript, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Mengambil callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Mengatur callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen Words atau Email.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Callback yang digunakan untuk memperkirakan kemajuan penyimpanan dokumen. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke parameter.  createPageStream  parameter. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya tersemat.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya, 'page\\_\\{0\\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Format jalur file, misalnya, 'page\\_\\{0\\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Metode yang melepaskan aliran yang dibuat oleh metode  createPageStream . |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Metode yang membuat URL untuk sumber daya HTML. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data sumber daya HTML output. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Metode yang membuat URL untuk sumber daya HTML. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metode yang melepaskan aliran yang dibuat oleh metode  createPageStream . |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Metode yang melepaskan aliran yang dibuat oleh metode  createResourceStream . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions  untuk merender ke HTML dengan sumber daya eksternal.

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Fabrik yang mengimplementasikan metode untuk membuat URL sumber daya dan menginstansiasi/melepaskan aliran sumber daya HTML output. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions .

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

File output akan ditempatkan ke direktori kerja saat ini dari aplikasi. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Menginisialisasi instance baru dari kelas  HtmlViewOptions .

Untuk contoh kode, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya, 'page\\_\\{0\\}.html'. |
| resourceFilePathFormat | java.lang.String | Format jalur file sumber daya, misalnya, 'page\\_\\{0\\}/resource\\_\\{1\\}'. |
| resourceUrlFormat | java.lang.String | Format URL sumber daya, misalnya, 'page\\_\\{0\\}/resource\\_\\{1\\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
