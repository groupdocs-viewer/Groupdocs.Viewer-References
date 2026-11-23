---
title: "PathUtils"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Kelas PathUtils menyediakan metode utilitas untuk bekerja dengan jalur file."
type: docs
weight: 13
url: /id/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Kelas PathUtils menyediakan metode utilitas untuk bekerja dengan jalur file.


Kelas PathUtils berisi metode statis yang memungkinkan Anda melakukan berbagai operasi
pada jalur file dalam komponen GroupDocs.Viewer.


Contoh penggunaan:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | Gabungkan bagian-bagian jalur menggunakan pemisah. |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | Mendapatkan nama file. |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Gabungkan bagian-bagian jalur menggunakan pemisah.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | params | java.lang.String[] | bagian-bagian jalur |
|

**Returns:**
java.lang.String - jalur hasil

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Mendapatkan nama file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | jalur | java.lang.String | jalur |
|

**Returns:**
java.lang.String - nama file

