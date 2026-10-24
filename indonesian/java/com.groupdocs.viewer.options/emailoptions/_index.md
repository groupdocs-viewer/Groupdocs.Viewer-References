---
title: "EmailOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender pesan email."
type: docs
weight: 14
url: /id/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Menyediakan opsi untuk merender pesan email.


Kelas EmailOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan
untuk mengontrol perenderan pesan email dalam komponen GroupDocs.Viewer.


Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


Contoh penggunaan:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | Menginisialisasi instance baru dari |
EmailOptions
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | Mendapatkan format waktu untuk nilai tanggal dan waktu. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Mendapatkan format waktu untuk nilai tanggal dan waktu. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Mendapatkan offset zona waktu untuk pesan. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Mendapatkan offset menit zona waktu untuk pesan. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Mendapatkan offset zona waktu untuk pesan. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Mendapatkan offset menit zona waktu untuk pesan. |
|
|  | [getPageSize()](#getPageSize--) | Mendapatkan ukuran halaman output. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Mendapatkan ukuran halaman output. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Mengambil pemetaan antara bidang pesan email dan representasi teksnya. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Menetapkan pemetaan antara bidang pesan email dan representasi teksnya. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Menimpa metode equals() dari kelas Object. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Menimpa metode toString() dari kelas Object. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Menginisialisasi instance baru dari
EmailOptions
kelas.
Konstruktor ini digunakan untuk membuat instance baru dari
EmailOptions
kelas dengan pengaturan default.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Mendapatkan format waktu untuk nilai tanggal dan waktu.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Jika format waktu tidak diatur, format sistem saat ini akan digunakan.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - format waktu untuk nilai tanggal dan waktu.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Mendapatkan format waktu untuk nilai tanggal dan waktu.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Jika format waktu tidak diatur, format sistem saat ini akan digunakan.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | Format waktu untuk nilai tanggal dan waktu. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Mendapatkan offset zona waktu untuk pesan.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - offset zona waktu.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Mendapatkan offset menit zona waktu untuk pesan.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - offset zona waktu.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Mendapatkan offset zona waktu untuk pesan.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | Offset zona waktu. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Mendapatkan offset menit zona waktu untuk pesan.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | offsetMinutes | int | Offset zona waktu. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Mendapatkan ukuran halaman output.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Mendapatkan ukuran halaman output.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Ukuran halaman. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Mengambil pemetaan antara bidang pesan email dan representasi teksnya.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - pemetaan antara bidang pesan email dan representasi teksnya.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Menetapkan pemetaan antara bidang pesan email dan representasi teksnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Pemetaan antara bidang pesan email dan representasi teksnya. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Menimpa metode equals() dari kelas Object.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | o | java.lang.Object | Objek untuk dibandingkan. |
|

**Returns:**
boolean - true jika objek-objek tersebut sama, false jika tidak.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Menghitung nilai kode hash untuk objek ini. Kode hash didasarkan pada
status internal objek dan digunakan dalam struktur data berbasis hash
seperti peta hash dan set hash.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - nilai kode hash untuk objek ini.

### toString() {#toString--}
```
public String toString()
```


Menimpa metode toString() dari kelas Object.


**Returns:**
java.lang.String - representasi string dari objek.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Mengembalikan representasi string dari objek ini.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | gaya | org.apache.commons.lang3.builder.ToStringStyle | ToStringStyle yang digunakan untuk menghasilkan representasi string. |
|

**Returns:**
java.lang.String - representasi string dari objek ini menggunakan ToStringStyle yang ditentukan.

