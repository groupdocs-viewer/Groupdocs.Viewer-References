---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili informasi tampilan untuk file arsip."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk file arsip.

Antarmuka ArchiveViewInfo mendefinisikan kontrak untuk mengambil informasi tampilan khusus file arsip dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengakses detail seperti jumlah halaman, dimensi, dan opsi rendering khusus file arsip.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFolders()](#getFolders--) | Mengambil daftar folder yang terdapat dalam file arsip. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Menetapkan daftar folder yang terdapat dalam file arsip. |
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


Menetapkan daftar folder yang terdapat dalam file arsip.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folder | java.util.List<java.lang.String> | daftar folder. |

