---
title: "OutlookOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan opsi untuk merender file data Outlook."
type: docs
weight: 20
url: /id/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Menyediakan opsi untuk merender file data Outlook.


Kelas OutlookOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan
untuk mengontrol rendering file data Outlook (seperti file PST atau OST) dalam komponen GroupDocs.Viewer.


Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Contoh penggunaan:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFolder()](#getFolder--) | Mendapatkan nama folder yang akan dirender. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Mengatur nama folder yang akan dirender. |
|
|  | [getTextFilter()](#getTextFilter--) | Mendapatkan kata kunci yang digunakan untuk memfilter pesan. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Mendapatkan kata kunci yang digunakan untuk memfilter pesan. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Mendapatkan alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Mengatur alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Mendapatkan jumlah maksimum pesan atau item yang dapat dirender dari satu folder. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Mengatur jumlah maksimum pesan atau item yang dapat dirender dari satu folder. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Mendapatkan nama folder yang akan dirender.
Nama folder (mis., Inbox, Sent Item, atau Deleted Items) yang akan dirender.


Saat merender file data Outlook, GroupDocs.Viewer merender pesan dari semua folder yang terdapat dalam file (termasuk folder bersarang). Gunakan properti ini untuk merender item dari folder tertentu.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) ini.


**Returns:**
java.lang.String - nama folder yang akan dirender.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Mengatur nama folder yang akan dirender.
Nama folder (mis., Inbox, Sent Item, atau Deleted Items) yang akan dirender.


Saat merender file data Outlook, GroupDocs.Viewer merender pesan dari semua folder yang terdapat dalam file (termasuk folder bersarang). Gunakan properti ini untuk merender item dari folder tertentu.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Nama folder yang akan dirender. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Mendapatkan kata kunci yang digunakan untuk memfilter pesan.


Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di subjek atau isi. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - kata kunci.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Mendapatkan kata kunci yang digunakan untuk memfilter pesan.


Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di subjek atau isi. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Kata kunci. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Mendapatkan alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima.


Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di alamat pengirim\ufffds atau penerima\ufffds. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - alamat email yang digunakan untuk memfilter pesan.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Mengatur alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima.


Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di alamat pengirim\ufffds atau penerima\ufffds. Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | java.lang.String | Alamat email yang digunakan untuk memfilter pesan. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Mendapatkan jumlah maksimum pesan atau item yang dapat dirender dari satu folder.


File data Outlook dapat berukuran besar dan mengambil semua pesan dapat memakan waktu yang signifikan.
Pengaturan ini membatasi jumlah maksimum pesan atau item (seperti kontak dan tugas) yang dirender.
Nilai default adalah 50. Atur nilai menjadi 0 untuk merender semua pesan.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - jumlah maksimum pesan atau item yang dapat dirender dari satu folder.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Mengatur jumlah maksimum pesan atau item yang dapat dirender dari satu folder.


File data Outlook dapat berukuran besar dan mengambil semua pesan dapat memakan waktu yang signifikan.
Pengaturan ini membatasi jumlah maksimum pesan atau item (seperti kontak dan tugas) yang dirender.
Nilai default adalah 50. Atur nilai menjadi 0 untuk merender semua pesan.
Untuk contoh kode, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nilai | int | Jumlah maksimum pesan atau item yang dapat dirender dari satu folder. |
|

