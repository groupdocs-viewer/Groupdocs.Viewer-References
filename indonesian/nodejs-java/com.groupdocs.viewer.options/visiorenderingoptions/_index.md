---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Berisi opsi untuk merender dokumen Visio."
type: docs
weight: 36
url: /id/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Berisi opsi untuk merender dokumen Visio.

Kelas VisioRenderingOptions menyediakan opsi untuk memproses dan merender file Visio dalam komponen GroupDocs.Viewer. Kelas ini mengenkapsulasi pengaturan dan parameter yang dapat digunakan untuk mengontrol proses rendering dan format output untuk dokumen Visio. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Menginisialisasi instance baru dari kelas  VisioRenderingOptions . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Render hanya gambar Visio, mengecualikan diagram. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Mengatur flag untuk merender hanya gambar Visio, mengecualikan diagram. |
| [getFigureWidth()](#getFigureWidth--) | Mengambil lebar gambar. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Mengatur lebar gambar. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Menginisialisasi instance baru dari kelas  VisioRenderingOptions .

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Render hanya gambar Visio, mengecualikan diagram.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  jika hanya gambar Visio yang harus dirender,  false  sebaliknya.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Mengatur flag untuk merender hanya gambar Visio, mengecualikan diagram.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  untuk merender hanya gambar Visio,  false  untuk menyertakan diagram. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Mengambil lebar gambar. Tinggi akan dihitung secara otomatis.

**Returns:**
int - lebar gambar.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Mengatur lebar gambar. Tinggi akan dihitung secara otomatis.

***Note:** Default value is 100.*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figureWidth | int | Lebar gambar. |

