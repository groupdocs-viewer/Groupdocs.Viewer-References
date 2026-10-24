---
title: "PresentationOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender presentasi."
type: docs
weight: 26
url: /id/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Menyediakan opsi untuk merender presentasi.


Untuk detail, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Mengaktifkan placeholder perenderan di header dan footer slide. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Mengaktifkan placeholder perenderan di header dan footer slide. |
|
|  | [getResolution()](#getResolution--) | Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan ke HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan ke HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation.


Dalam mode ini, file Presentation dirender menjadi markup HTML/CSS murni, tanpa gambar SVG.
Secara default, fitur ini dinonaktifkan (false). Perender HTML berbasis SVG yang ada akan digunakan jika opsi ini tidak diaktifkan.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation.


Dalam mode ini, file Presentation dirender menjadi markup HTML/CSS murni, tanpa gambar SVG.
Secara default, fitur ini dinonaktifkan (false). Perender HTML berbasis SVG yang ada akan digunakan jika opsi ini tidak diaktifkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Mengaktifkan rendering placeholder di header dan footer slide. Dinonaktifkan secara default (false). Opsi ini berlaku untuk semua 4 mode rendering presentasi: HTML, PDF, PNG, dan JPEG. Tidak berlaku saat merender presentasi ke markup HTML/CSS murni menggunakan .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Mengaktifkan rendering placeholder di header dan footer slide. Dinonaktifkan secara default (false). Opsi ini berlaku untuk semua 4 mode rendering presentasi: HTML, PDF, PNG, dan JPEG. Tidak berlaku saat merender presentasi ke markup HTML/CSS murni menggunakan .


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan ke HTML/PDF).


Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan ke HTML/PDF).


Untuk contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

