---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender file manajemen proyek."
type: docs
weight: 27
url: /id/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Menyediakan opsi untuk merender file manajemen proyek.

Kelas ProjectManagementOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk mengontrol rendering file manajemen proyek (seperti Microsoft Project atau serupa) dalam komponen GroupDocs.Viewer. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Menginisialisasi instance baru dari kelas  ProjectManagementOptions . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageSize()](#getPageSize--) | Mengambil ukuran halaman output. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Mengatur ukuran halaman output. |
| [getTimeUnit()](#getTimeUnit--) | Mengambil satuan waktu. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Mengambil satuan waktu. |
| [getStartDate()](#getStartDate--) | Mengambil tanggal mulai tampilan Gantt Chart yang akan disertakan dalam output. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Mengatur tanggal mulai tampilan Gantt Chart yang akan disertakan dalam output. |
| [getEndDate()](#getEndDate--) | Mengambil tanggal akhir tampilan Gantt Chart yang akan disertakan dalam output. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Mengatur tanggal akhir tampilan Gantt Chart yang akan disertakan dalam output. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Menginisialisasi instance baru dari kelas  ProjectManagementOptions .

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Mengambil ukuran halaman output.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Mengatur ukuran halaman output.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Ukuran halaman output. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Mengambil satuan waktu.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Mengambil satuan waktu.

Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Satuan waktu. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Mengambil tanggal mulai tampilan Gantt Chart yang akan disertakan dalam output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - tanggal mulai tampilan Gantt Chart.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Mengatur tanggal mulai tampilan Gantt Chart yang akan disertakan dalam output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date | Tanggal mulai tampilan Gantt Chart. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Mengambil tanggal akhir tampilan Gantt Chart yang akan disertakan dalam output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - tanggal akhir tampilan Gantt Chart.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Mengatur tanggal akhir tampilan Gantt Chart yang akan disertakan dalam output.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date | Tanggal akhir tampilan Gantt Chart. |

