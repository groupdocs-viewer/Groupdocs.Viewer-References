---
title: "TextOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Opsi pemisahan file teks menjadi halaman."
type: docs
weight: 32
url: /id/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Opsi pemisahan file teks menjadi halaman.


Kelas TextOptions menyediakan opsi untuk membagi file teks menjadi halaman dalam komponen GroupDocs.Viewer.
Ini memungkinkan Anda mengontrol bagaimana file teks dibagi menjadi halaman individual untuk tujuan rendering dan penampilan.


Contoh penggunaan:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Menginisialisasi instance baru dari |
TextOptions
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Mendapatkan jumlah maksimum karakter per baris pada halaman. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Mengatur jumlah maksimum karakter per baris pada halaman. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Mendapatkan jumlah maksimum baris per halaman. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Mengatur jumlah maksimum baris per halaman. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Menginisialisasi instance baru dari
TextOptions
kelas.
Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Mendapatkan jumlah maksimum karakter per baris pada halaman.


***Note:** The default value is 85.*
Nilai default adalah 85. Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - jumlah maksimum karakter per baris pada halaman.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Mengatur jumlah maksimum karakter per baris pada halaman.


***Note:** The default value is 85.*
Nilai default adalah 85. Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxCharsPerRow | int | Jumlah maksimum karakter per baris pada halaman. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Mendapatkan jumlah maksimum baris per halaman.


***Note:** The default value is 55.*
Nilai default adalah 55. Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - jumlah maksimum baris.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Mengatur jumlah maksimum baris per halaman.


***Note:** The default value is 55.*
Nilai default adalah 55. Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxRowsPerPage | int | Jumlah maksimum baris. |
|

