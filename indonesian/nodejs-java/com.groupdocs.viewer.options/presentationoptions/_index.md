---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender opsi presentasi."
type: docs
weight: 26
url: /id/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Menyediakan opsi untuk merender opsi presentasi.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation. |
| [getResolution()](#getResolution--) | Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan HTML/PDF). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan HTML/PDF). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation.

Dalam mode ini, file Presentation dirender menjadi markup HTML/CSS murni, tanpa gambar SVG. Secara default, fitur ini dinonaktifkan (false). Renderer HTML berbasis SVG yang ada akan digunakan jika opsi ini tidak diaktifkan.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Mengaktifkan mode perenderan HTML baru untuk dokumen Presentation.

Dalam mode ini, file Presentation dirender menjadi markup HTML/CSS murni, tanpa gambar SVG. Secara default, fitur ini dinonaktifkan (false). Renderer HTML berbasis SVG yang ada akan digunakan jika opsi ini tidak diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan HTML/PDF).

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolusi untuk gambar di dalam presentasi (hanya untuk perenderan HTML/PDF).

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

