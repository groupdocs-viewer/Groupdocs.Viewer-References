---
title: "Watermark"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili watermark teks."
type: docs
weight: 37
url: /id/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Mewakili watermark teks. Untuk detail, lihat [documentation][].

Kelas Watermark mewakili watermark teks dalam komponen GroupDocs.Viewer. Kelas ini digunakan untuk mendefinisikan dan menerapkan watermark pada output hasil render dokumen.

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


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas  Watermark  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getText()](#getText--) | Mengembalikan teks watermark. |
| [getColor()](#getColor--) | Mengembalikan warna watermark. |
| [getColorAsHex()](#getColorAsHex--) | Mengembalikan warna watermark dalam format heks. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Mengatur warna watermark. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Mengatur warna watermark. |
| [getPosition()](#getPosition--) | Mengembalikan posisi watermark. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Mengatur posisi watermark. |
| [getSize()](#getSize--) | Mengembalikan ukuran watermark. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Mengatur ukuran watermark. |
| [getFontName()](#getFontName--) | Mengembalikan nama font yang digunakan untuk watermark. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Mengatur nama font yang digunakan untuk watermark. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Menginisialisasi sebuah instance baru dari kelas  Watermark  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | Teks watermark. |

### getText() {#getText--}
```
public final String getText()
```


Mengembalikan teks watermark. Metode ini mengambil teks watermark yang diterapkan pada dokumen.

**Returns:**
java.lang.String - teks watermark.
### getColor() {#getColor--}
```
public final Color getColor()
```


Mengembalikan warna watermark. Metode ini mengambil warna watermark yang diterapkan pada dokumen.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - warna watermark.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Mengembalikan warna watermark dalam format heks. Metode ini mengambil warna watermark yang diterapkan pada dokumen.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - warna watermark dalam format heks.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Mengatur warna watermark. Metode ini mengatur warna watermark yang diterapkan pada dokumen.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Color | Warna watermark yang akan diatur. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Mengatur warna watermark. Metode ini mengatur warna watermark yang diterapkan pada dokumen.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| colorName | java.lang.String | Warna watermark yang akan diatur. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Mengembalikan posisi watermark. Metode ini mengembalikan posisi watermark yang diterapkan pada dokumen.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Mengatur posisi watermark. Metode ini mengatur posisi watermark yang diterapkan pada dokumen.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | Posisi watermark. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Mengembalikan ukuran watermark. Metode ini mengambil ukuran watermark yang diterapkan pada dokumen.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Mengatur ukuran watermark. Metode ini mengatur ukuran watermark yang akan diterapkan pada dokumen.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | Ukuran watermark. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Mengembalikan nama font yang digunakan untuk watermark.

**Returns:**
java.lang.String - nama font yang digunakan untuk watermark.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Mengatur nama font yang digunakan untuk watermark.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String | Nama font yang digunakan untuk watermark. |

