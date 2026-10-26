---
title: "TimeUnit"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Satuan waktu durasi proyek."
type: docs
weight: 47
url: /id/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Satuan waktu durasi proyek.

Enum TimeUnit mewakili unit waktu yang berbeda untuk menentukan durasi proyek dalam komponen GroupDocs.Viewer. Ini menyediakan sekumpulan unit waktu yang telah ditentukan yang dapat digunakan untuk merepresentasikan dan menghitung durasi proyek, seperti hari, bulan, dan sebagainya. Untuk detail, lihat [documentation][].

Contoh penggunaan:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Skala waktu tidak diketahui. |
| [DAYS](#DAYS) | Skala waktu hari. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Skala waktu sepertiga bulan. |
| [MONTHS](#MONTHS) | Skala waktu bulan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Skala waktu tidak diketahui. Unit waktu ini mewakili skala waktu yang tidak diketahui atau tidak ditentukan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Skala waktu hari. Unit waktu ini mewakili interval satu hari.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Skala waktu sepertiga bulan. Unit waktu ini mewakili interval sepertiga bulan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Skala waktu bulan. Unit waktu ini mewakili interval satu bulan.

Untuk detail, lihat [dokumentasi][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
