---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili informasi tampilan untuk dokumen MS Project."
type: docs
weight: 23
url: /id/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk dokumen MS Project.

Antarmuka ProjectManagementViewInfo mendefinisikan kontrak untuk mengakses dan memanipulasi informasi tampilan untuk dokumen MS Project dalam komponen GroupDocs.Viewer. Antarmuka ini menyediakan metode untuk mengambil informasi seperti tanggal mulai dan selesai, serta properti lainnya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getStartDate()](#getStartDate--) | Mengambil tanggal dan waktu ketika proyek dimulai. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Mengatur tanggal dan waktu mulai proyek. |
| [getEndDate()](#getEndDate--) | Mengambil tanggal dan waktu ketika proyek selesai. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Mengatur tanggal dan waktu selesai proyek. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Mengambil tanggal dan waktu ketika proyek dimulai.

**Returns:**
java.util.Date - tanggal dan waktu mulai proyek.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Mengatur tanggal dan waktu mulai proyek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startDate | java.util.Date | tanggal dan waktu mulai baru yang akan diatur. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Mengambil tanggal dan waktu ketika proyek selesai.

**Returns:**
java.util.Date - tanggal dan waktu selesai proyek.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Mengatur tanggal dan waktu selesai proyek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| endDate | java.util.Date | tanggal dan waktu selesai baru yang akan diatur. |

