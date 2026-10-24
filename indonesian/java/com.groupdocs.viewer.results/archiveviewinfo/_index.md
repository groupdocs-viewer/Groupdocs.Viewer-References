---
title: "ArchiveViewInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili informasi tampilan untuk file arsip."
type: docs
weight: 11
url: /id/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk file arsip.


Antarmuka ArchiveViewInfo mendefinisikan kontrak untuk mengambil informasi tampilan yang spesifik untuk file arsip
di komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengakses detail seperti jumlah halaman, dimensi, dan opsi rendering
spesifik untuk file arsip.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFolders()](#getFolders--) | Mengambil daftar folder yang terdapat dalam file arsip. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Mengatur daftar folder yang terdapat dalam file arsip. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Mengambil daftar folder yang terdapat dalam file arsip.


**Returns:**
java.util.List<java.lang.String> - daftar folder.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Mengatur daftar folder yang terdapat dalam file arsip.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | folder | java.util.List<java.lang.String> | daftar folder. |
|

