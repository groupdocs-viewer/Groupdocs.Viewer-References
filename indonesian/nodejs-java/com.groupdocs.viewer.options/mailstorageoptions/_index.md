---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Menyediakan opsi untuk merender file data Mail storage Lotus Notes MBox."
type: docs
weight: 19
url: /id/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Menyediakan opsi untuk merender file data penyimpanan Mail (Lotus Notes, MBox).

Kelas MailStorageOptions mengenkapsulasi berbagai pengaturan dan parameter yang dapat digunakan untuk mengontrol perenderan file data Mail storage (seperti Lotus Notes atau MBox) dalam komponen GroupDocs.Viewer.

Untuk detail, lihat [dokumentasi][].

Contoh penggunaan:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Mendapatkan kata kunci yang digunakan untuk memfilter pesan. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Mengatur kata kunci yang digunakan untuk memfilter pesan. |
| [getAddressFilter()](#getAddressFilter--) | Mendapatkan alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Mengatur alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima. |
| [getMaxItems()](#getMaxItems--) | Mendapatkan jumlah maksimum pesan atau item yang akan dirender. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Mengatur jumlah maksimum pesan atau item yang akan dirender. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Mendapatkan kata kunci yang digunakan untuk memfilter pesan.

Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di subjek atau isi. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - kata kunci yang digunakan untuk memfilter pesan.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Mengatur kata kunci yang digunakan untuk memfilter pesan.

Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di subjek atau isi. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textFilter | java.lang.String | Kata kunci yang digunakan untuk memfilter pesan. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Mendapatkan alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima.

Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di alamat pengirim atau penerima. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - alamat email yang digunakan untuk memfilter pesan.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Mengatur alamat email yang digunakan untuk memfilter pesan berdasarkan pengirim atau penerima.

Gunakan properti ini untuk merender semua pesan yang berisi teks tertentu di alamat pengirim atau penerima. Untuk contoh kode, lihat [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| addressFilter | java.lang.String | Alamat email yang digunakan untuk menyaring pesan. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Mendapatkan jumlah maksimum pesan atau item yang akan dirender.

File data Lotus Notes dapat berukuran besar, dan mengambil semua pesan dapat memakan waktu yang signifikan. Pengaturan ini membatasi jumlah maksimum pesan atau item yang ditampilkan.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - jumlah maksimum pesan atau item yang akan ditampilkan.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Mengatur jumlah maksimum pesan atau item yang akan dirender.

File data Lotus Notes dapat berukuran besar, dan mengambil semua pesan dapat memakan waktu yang signifikan. Pengaturan ini membatasi jumlah maksimum pesan atau item yang ditampilkan.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| maxItems | int | Jumlah maksimum pesan atau item yang akan ditampilkan. |

