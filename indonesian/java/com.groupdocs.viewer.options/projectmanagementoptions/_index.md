---
title: "ProjectManagementOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender file manajemen proyek."
type: docs
weight: 27
url: /id/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Menyediakan opsi untuk merender file manajemen proyek.


Kelas ProjectManagementOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan
untuk mengontrol perenderan file manajemen proyek (seperti Microsoft Project atau serupa)
dalam komponen GroupDocs.Viewer.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


Contoh penggunaan:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | Menginisialisasi instance baru dari |
ProjectManagementOptions
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Mengambil ukuran halaman output. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Mengatur ukuran halaman output. |
|
|  | [getTimeUnit()](#getTimeUnit--) | Mengambil satuan waktu. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Mengambil satuan waktu. |
|
|  | [getStartDate()](#getStartDate--) | Mengambil tanggal mulai Tampilan Gantt Chart yang akan dimasukkan dalam output. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | Mengatur tanggal mulai Tampilan Gantt Chart yang akan dimasukkan dalam output. |
|
|  | [getEndDate()](#getEndDate--) | Mengambil tanggal akhir Tampilan Gantt Chart yang akan dimasukkan dalam output. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | Mengatur tanggal akhir Tampilan Gantt Chart yang akan dimasukkan dalam output. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Menginisialisasi instance baru dari
ProjectManagementOptions
kelas.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Mengambil ukuran halaman output.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Mengatur ukuran halaman output.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Ukuran halaman output. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Mengambil satuan waktu.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Mengambil satuan waktu.


Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Satuan waktu. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Mengambil tanggal mulai Tampilan Gantt Chart yang akan dimasukkan dalam output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - tanggal mulai Tampilan Gantt Chart.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Mengatur tanggal mulai Tampilan Gantt Chart yang akan dimasukkan dalam output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.Date | Tanggal mulai Tampilan Gantt Chart. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Mengambil tanggal akhir Tampilan Gantt Chart yang akan dimasukkan dalam output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - tanggal akhir Tampilan Gantt Chart.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Mengatur tanggal akhir Tampilan Gantt Chart yang akan dimasukkan dalam output.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.Date | Tanggal akhir Tampilan Gantt Chart. |
|

