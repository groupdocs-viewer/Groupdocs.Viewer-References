---
title: "Resource"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili sumber daya HTML seperti font, gaya, gambar, atau grafik."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Mewakili sumber daya HTML seperti font, gaya, gambar, atau grafik.

Kelas Resource mewakili sumber daya yang digunakan dalam rendering HTML pada komponen GroupDocs.Viewer. Ini dapat mewakili berbagai jenis sumber daya, seperti font, gaya, gambar, atau grafik, yang termasuk atau dirujuk dalam output HTML yang dihasilkan selama proses rendering.

Contoh penggunaan:

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Membuat instance baru dari kelas Resource. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFileName()](#getFileName--) | Mengembalikan nama file dari resource. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Mengatur nama file dari resource. |
| [isNested()](#isNested--) | Mengembalikan apakah resource berada di dalam resource lain, misalnya resource font yang berada dalam resource CSS atau SVG. |
| [setNested(boolean nested)](#setNested-boolean-) | Mengatur apakah resource berada di dalam resource lain. |
| [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Membuat instance baru dari kelas Resource.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file resource. |
| bersarang | boolean | Menunjukkan apakah resource berada di dalam resource lain, misalnya, resource font yang berada dalam resource CSS atau SVG. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Mengembalikan nama file dari resource.

**Returns:**
java.lang.String - nama file dari resource.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Mengatur nama file dari resource.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | java.lang.String | Nama file baru untuk resource. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Mengembalikan apakah resource berada di dalam resource lain, misalnya resource font yang berada dalam resource CSS atau SVG.

**Returns:**
boolean - Apakah resource berada di dalam resource lain.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Mengatur apakah resource berada di dalam resource lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bersarang | boolean | Apakah resource harus diatur sebagai bersarang. |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.

**Returns:**
java.lang.String - representasi string dari objek saat ini.
