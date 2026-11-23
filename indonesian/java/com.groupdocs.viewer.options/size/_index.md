---
title: "Size"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Berisi ukuran watermark."
type: docs
weight: 30
url: /id/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Berisi ukuran watermark.


Kelas Size mewakili ukuran watermark dalam komponen GroupDocs.Viewer.
Itu menyediakan opsi untuk menentukan dimensi watermark, seperti lebar dan tinggi.


Contoh penggunaan:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Menginisialisasi instance baru dari |
Size
kelas.
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Mewakili ukuran maksimum teks watermark yang cocok dengan halaman. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Mewakili setengah ukuran maksimum teks watermark yang cocok dengan halaman. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Mewakili sepertiga ukuran maksimum teks watermark yang cocok dengan halaman. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Mengembalikan ukuran teks watermark dalam persentase relatif terhadap lebar halaman. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Menginisialisasi instance baru dari
Size
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | relativeSize | byte | Ukuran dalam persentase relatif terhadap ukuran halaman. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Mewakili ukuran maksimum teks watermark yang cocok dengan halaman.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Mewakili setengah ukuran maksimum teks watermark yang cocok dengan halaman.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Mewakili sepertiga ukuran maksimum teks watermark yang cocok dengan halaman.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Mengembalikan ukuran teks watermark dalam persentase relatif terhadap lebar halaman.


**Returns:**
byte - ukuran teks watermark dalam persentase.

