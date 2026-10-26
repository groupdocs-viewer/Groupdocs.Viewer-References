---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mengkapsulkan meta-informasi dan data biner dari satu font dalam dokumen PDF yang dimuat ke dalam instance Viewer."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Mengkapsulasi meta-informasi dan data biner dari satu font dalam dokumen PDF, yang dimuat ke dalam instance Viewer.

Font ini digunakan dalam konten dokumen dan merupakan salah satu dari:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Konstruktor internal yang digunakan oleh ekstraksi font PDF. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Mendapatkan nama keluarga font. |
| [getStyle()](#getStyle--) | Mendapatkan gaya font ini. |
| [isEmbedded()](#isEmbedded--) | Mengembalikan apakah font disematkan di dalam dokumen PDF. |
| [isInstalled()](#isInstalled--) | Mengembalikan apakah font terpasang di OS. |
| [getFormat()](#getFormat--) | Mengembalikan format file font. |
| [getContent()](#getContent--) | Mengembalikan konten biner font. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Menyerialkan font ini sebagai aturan CSS @font-face. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Konstruktor internal yang digunakan oleh ekstraksi font PDF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| familyName | java.lang.String | nama keluarga font |
| gaya | com.groupdocs.viewer.fonts.FontStyles | gaya (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true jika font disematkan dalam PDF |
| isInstalled | boolean | true jika font terpasang di OS |
| content | byte[] | data font biner (nullable) |
| format | int | format file font |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Mendapatkan nama keluarga font.

**Returns:**
java.lang.String - string nama keluarga (tidak pernah null atau kosong)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Mendapatkan gaya font ini.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - gaya font
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Mengembalikan apakah font disematkan di dalam dokumen PDF.

**Returns:**
boolean - true jika disematkan
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Mengembalikan apakah font terpasang di OS.

**Returns:**
boolean - true jika terpasang
### getFormat() {#getFormat--}
```
public int getFormat()
```


Mengembalikan format file font.

**Returns:**
int - enum format font
### getContent() {#getContent--}
```
public byte[] getContent()
```


Mengembalikan konten biner font.

**Returns:**
byte[] - array byte atau null jika tidak tersedia
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Menyerialkan font ini sebagai aturan CSS @font-face.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keluaran | java.io.Writer | penulis tempat CSS akan ditulis |

