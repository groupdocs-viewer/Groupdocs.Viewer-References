---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili informasi tampilan untuk file Data Outlook."
type: docs
weight: 20
url: /id/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk file Data Outlook.

Antarmuka OutlookViewInfo mendefinisikan kontrak untuk mengakses dan memanipulasi informasi tampilan untuk file Data Outlook dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti daftar folder, dan properti lainnya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFolders()](#getFolders--) | Mengambil daftar folder yang terdapat dalam file Data Outlook. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Mengatur daftar folder yang terdapat dalam file Data Outlook. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Mengambil daftar folder yang terdapat dalam file Data Outlook.

**Returns:**
java.util.List<java.lang.String> - daftar folder.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Mengatur daftar folder yang terdapat dalam file Data Outlook.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| daftar | java.util.List<java.lang.String> | daftar folder. |

