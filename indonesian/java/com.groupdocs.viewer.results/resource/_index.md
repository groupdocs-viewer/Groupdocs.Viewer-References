---
title: "Resource"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili sumber daya HTML seperti font, gaya, gambar, atau grafik."
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Mewakili sumber daya HTML seperti font, gaya, gambar, atau grafik.


Kelas Resource mewakili sumber daya yang digunakan dalam rendering HTML pada komponen GroupDocs.Viewer.
Ini dapat mewakili berbagai jenis sumber daya, seperti font, gaya, gambar, atau grafik, yang termasuk
atau direferensikan dalam output HTML yang dihasilkan selama proses rendering.


Contoh penggunaan:

````

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
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Membuat instance baru dari |
Resource
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFileName()](#getFileName--) | Mengembalikan nama file sumber daya. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | Mengatur nama file sumber daya. |
|
|  | [isNested()](#isNested--) | Mengembalikan apakah sumber daya berada di dalam sumber daya lain, misalnya sumber daya font yang berada dalam sumber daya CSS atau SVG. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | Mengatur apakah sumber daya berada di dalam sumber daya lain. |
|
|  | [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Membuat instance baru dari
Resource
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | java.lang.String | Nama file sumber daya. |
|
|  | bersarang | boolean | Menunjukkan apakah sumber daya berada di dalam sumber daya lain, misalnya, sumber daya font yang berada dalam sumber daya CSS atau SVG. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Mengembalikan nama file sumber daya.


**Returns:**
java.lang.String - nama file sumber daya.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Mengatur nama file sumber daya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | java.lang.String | Nama file baru untuk sumber daya. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


Mengembalikan apakah sumber daya berada di dalam sumber daya lain, misalnya sumber daya font yang berada dalam sumber daya CSS atau SVG.


**Returns:**
boolean - Apakah sumber daya berada di dalam sumber daya lain.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Mengatur apakah sumber daya berada di dalam sumber daya lain.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | bersarang | boolean | Apakah sumber daya harus diatur sebagai bersarang. |
|

### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.


**Returns:**
java.lang.String - representasi string dari objek saat ini.

