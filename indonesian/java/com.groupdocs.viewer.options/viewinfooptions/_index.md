---
title: "ViewInfoOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi yang digunakan untuk mengambil informasi tentang tampilan."
type: docs
weight: 34
url: /id/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Menyediakan opsi yang digunakan untuk mengambil informasi tentang tampilan.


Kelas ViewInfoOptions mengenkapsulasi pengaturan tambahan dan parameter yang
dapat digunakan untuk mengambil informasi tentang tampilan dalam komponen GroupDocs.Viewer.


Contoh penggunaan:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Menunjukkan apakah ekstraksi teks diaktifkan. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Mengatur flag yang menunjukkan apakah ekstraksi teks diaktifkan. |
|
|  | [getMaxWidth()](#getMaxWidth--) | Mengembalikan lebar maksimum gambar output untuk rendering ke PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Mengatur lebar maksimum gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [getMaxHeight()](#getMaxHeight--) | Mengembalikan tinggi maksimum gambar output untuk rendering ke PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Mengatur tinggi maksimum gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [getWidth()](#getWidth--) | Lebar gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [setWidth(int width)](#setWidth-int-) | Lebar gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [getHeight()](#getHeight--) | Tinggi gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [setHeight(int height)](#setHeight-int-) | Tinggi gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG). |
|
|  | [forHtmlView()](#forHtmlView--) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke HTML.
|
|  | [forJpgView()](#forJpgView--) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke JPG.
|
|  | [forPngView()](#forPngView--) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke PNG.
|
|  | [forPdfView()](#forPdfView--) | Menginisialisasi instance baru dari kelas ViewInfoOptions untuk mengambil informasi tentang tampilan saat rendering ke PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas berdasarkan objek [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas berdasarkan objek [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Menginisialisasi instance baru dari |
ViewInfoOptions
kelas berdasarkan objek [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Menginisialisasi instance baru dari kelas [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) berdasarkan objek PdfViewOptions. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Menunjukkan apakah ekstraksi teks diaktifkan.
Gunakan properti ini untuk mendapatkan teks yang terdapat dalam dokumen sumber dan koordinatnya. Kemudian Anda dapat menggunakan data ini untuk menambahkan teks yang dapat dipilih di atas gambar atau untuk mengimplementasikan pencarian teks dalam rendering berbasis gambar. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - True jika ekstraksi teks diaktifkan, false jika tidak.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Mengatur flag yang menunjukkan apakah ekstraksi teks diaktifkan.
Gunakan properti ini untuk mendapatkan teks yang terdapat dalam dokumen sumber dan koordinatnya. Kemudian Anda dapat menggunakan data ini untuk menambahkan teks yang dapat dipilih di atas gambar atau untuk mengimplementasikan pencarian teks dalam rendering berbasis gambar. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | extractText | boolean | True untuk mengaktifkan ekstraksi teks, false untuk menonaktifkannya. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Mengembalikan lebar maksimum gambar output untuk rendering ke PNG/JPG.
Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Returns:**
int - lebar maksimum gambar keluaran.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Mengatur lebar maksimum gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur lebar maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxWidth | int | Lebar maksimum gambar keluaran. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Mengembalikan tinggi maksimum gambar output untuk rendering ke PNG/JPG.
Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Returns:**
int - tinggi maksimum gambar keluaran.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Mengatur tinggi maksimum gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur tinggi maksimum gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxHeight | int | Tinggi maksimum gambar keluaran. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


Lebar gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Returns:**
int - lebar gambar.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Lebar gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur lebar gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Jika Anda mengatur properti ini, properti ini akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | width | int | Lebar gambar. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


Tinggi gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Jika Anda mengatur properti ini, properti akan diabaikan.


**Returns:**
int - tinggi gambar.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Tinggi gambar output (dalam piksel, hanya untuk rendering ke PNG/JPG).
Gunakan properti ini untuk mengatur tinggi gambar output (dalam piksel). Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Jika Anda mengatur properti ini, properti akan diabaikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | tinggi | int | Tinggi gambar. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | renderSinglePage | boolean | Mengaktifkan konten HTML untuk dirender pada satu halaman. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke JPG.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | extractText | boolean | Mengaktifkan ekstraksi teks. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas untuk mengambil informasi tentang tampilan saat rendering ke PNG.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | extractText | boolean | Mengaktifkan ekstraksi teks. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Menginisialisasi instance baru dari kelas ViewInfoOptions untuk mengambil informasi tentang tampilan saat rendering ke PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas berdasarkan objek [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Opsi tampilan HTML. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas berdasarkan objek [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Opsi tampilan PNG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Menginisialisasi instance baru dari
ViewInfoOptions
kelas berdasarkan objek [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Opsi tampilan JPG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Menginisialisasi instance baru dari kelas [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) berdasarkan objek PdfViewOptions.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Opsi tampilan PDF. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

