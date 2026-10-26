---
title: "Size"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Berisi ukuran watermark."
type: docs
weight: 30
url: /id/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Berisi ukuran watermark.

Kelas Size merepresentasikan ukuran watermark dalam komponen GroupDocs.Viewer. Kelas ini menyediakan opsi untuk menentukan dimensi watermark, seperti lebar dan tinggi.

Contoh penggunaan:

```

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
 
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Menginisialisasi instance baru dari kelas Size. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Merepresentasikan ukuran maksimum teks watermark yang sesuai dengan halaman. |
| [HALF_SIZE](#HALF-SIZE) | Merepresentasikan setengah dari ukuran maksimum teks watermark yang sesuai dengan halaman. |
| [ONE_THIRD](#ONE-THIRD) | Merepresentasikan sepertiga dari ukuran maksimum teks watermark yang sesuai dengan halaman. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Mengembalikan ukuran teks watermark dalam persentase relatif terhadap lebar halaman. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Menginisialisasi instance baru dari kelas Size.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| relativeSize | byte | Ukuran dalam persentase relatif terhadap ukuran halaman. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Merepresentasikan ukuran maksimum teks watermark yang sesuai dengan halaman.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Merepresentasikan setengah dari ukuran maksimum teks watermark yang sesuai dengan halaman.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Merepresentasikan sepertiga dari ukuran maksimum teks watermark yang sesuai dengan halaman.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Mengembalikan ukuran teks watermark dalam persentase relatif terhadap lebar halaman.

**Returns:**
byte - ukuran teks watermark dalam persentase.
