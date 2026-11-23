---
title: "FileName"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili nama file dalam arsip."
type: docs
weight: 15
url: /id/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Mewakili nama file dalam arsip.


Kelas FileName mengenkapsulasi nama file tanpa informasi jalur atau direktori apa pun.
Ia menyediakan metode untuk memanipulasi dan mengambil informasi tentang nama file.


Contoh penggunaan:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | Menginisialisasi instance baru dari |
FileName
kelas.
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [EMPTY](#EMPTY) | Mewakili nama file kosong. |
|
|  | [SOURCE](#SOURCE) | Mewakili nama file sumber. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | Mengembalikan representasi string dari objek saat ini. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Menginisialisasi instance baru dari
FileName
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileName | java.lang.String | Nama file. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Mewakili nama file kosong.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Mewakili nama file sumber.


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari objek saat ini.


**Returns:**
java.lang.String - representasi string dari objek saat ini.

