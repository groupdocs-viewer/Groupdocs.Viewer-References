---
title: "ArchiveOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender file arsip."
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Menyediakan opsi untuk merender file arsip.


The
ArchiveOptions
kelas mewakili sekumpulan opsi yang dapat digunakan untuk mengonfigurasi rendering file arsip dalam modul penampil.
Ini memungkinkan Anda menyesuaikan berbagai aspek proses rendering, seperti jumlah item per halaman dan sebagainya.


Contoh penggunaan:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
kelas menyediakan berbagai opsi penyesuaian untuk rendering file arsip.
Anda dapat mengonfigurasi opsi ini berdasarkan kebutuhan spesifik Anda untuk mencapai output yang diinginkan.*

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Membuat instance baru dari kelas ArchiveOptions dengan pengaturan default. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFolder()](#getFolder--) | Mendapatkan folder di dalam arsip yang akan digunakan untuk rendering. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Mengatur folder di dalam arsip yang akan digunakan untuk rendering. |
|
|  | [getFileName()](#getFileName--) | Mendapatkan nama file yang akan ditampilkan di header. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Mengatur nama file yang akan ditampilkan di header. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Membuat instance baru dari kelas ArchiveOptions dengan pengaturan default.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Mendapatkan folder di dalam arsip yang akan digunakan untuk rendering.


Secara default, GroupDocs.Viewer merender item dari semua folder yang terdapat dalam arsip. Untuk merender item dari folder tertentu, atur properti ini.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - folder yang akan dirender.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Mengatur folder di dalam arsip yang akan digunakan untuk rendering.


Secara default, GroupDocs.Viewer merender item dari semua folder yang terdapat dalam arsip. Untuk merender item dari folder tertentu, atur properti ini.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Folder yang akan dirender. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Mendapatkan nama file yang akan ditampilkan di header.


Secara default, GroupDocs.Viewer menampilkan nama file arsip di header setiap halaman. Untuk mengubah atau menyembunyikan nama ini, atur properti ini.
Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Mengatur nama file yang akan ditampilkan di header.


Secara default, GroupDocs.Viewer menampilkan nama file arsip di header setiap halaman. Untuk mengubah atau menyembunyikan nama ini, atur properti ini.
Untuk informasi lebih lanjut dan contoh kode, lihat [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Nama file yang akan ditampilkan. |
|

