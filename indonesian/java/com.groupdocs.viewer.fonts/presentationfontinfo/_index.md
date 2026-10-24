---
title: "PresentationFontInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mengkapsulkan metadata dan data biner dari font yang digunakan dalam dokumen Presentation yang dimuat ke dalam instance Viewer."
type: docs
weight: 15
url: /id/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Mengkapsulkan metadata dan data biner dari font yang digunakan dalam dokumen Presentation, dimuat ke dalam instance Viewer. Font ini digunakan dalam konten dokumen dan dapat disematkan di dalam dokumen itu sendiri atau diinstal di sistem operasi tempat GroupDocs.Viewer berjalan.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Mendapatkan nama keluarga font (tidak pernah null atau kosong). |
|
|  | [getStyle()](#getStyle--) | Mendapatkan gaya font: Regular, Bold, Italic, atau BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Menunjukkan apakah font ini disematkan di dalam dokumen yang dimuat ke dalam instance Viewer. |
|
|  | [getFormat()](#getFormat--) | Mendapatkan format font (TrueType, OpenType, dll.). |
|
|  | [getContent()](#getContent--) | Mendapatkan konten font biner, atau null jika data font tidak tersedia. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Menyerialkan info font ini ke dalam aturan CSS @font-face menggunakan penulis yang ditentukan. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Mendapatkan nama keluarga font (tidak pernah null atau kosong).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Mendapatkan gaya font: Regular, Bold, Italic, atau BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Menunjukkan apakah font ini disematkan di dalam dokumen yang dimuat ke dalam instance Viewer. Catatan: Dokumen Spreadsheet tidak dapat berisi font yang disematkan, sehingga untuk mereka selalu mengembalikan false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Mendapatkan format font (TrueType, OpenType, dll.). Jika hanya metadata yang tersedia, mengembalikan FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Mendapatkan konten font biner, atau null jika data font tidak tersedia.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Menyerialkan info font ini ke dalam aturan CSS @font-face menggunakan penulis yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | output | java.io.Writer | penulis untuk menulis CSS ke dalamnya (tidak boleh null) |
|

