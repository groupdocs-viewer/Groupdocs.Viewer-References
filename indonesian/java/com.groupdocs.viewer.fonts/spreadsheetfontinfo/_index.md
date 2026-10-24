---
title: "SpreadsheetFontInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mengkapsulkan metadata dan data biner dari satu font dari dokumen Spreadsheet yang dimuat ke dalam instance Viewer."
type: docs
weight: 16
url: /id/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Mengkapsulkan metadata dan data biner dari satu font dari dokumen Spreadsheet, yang dimuat ke dalam instance Viewer. Dokumen Spreadsheet tidak dapat memiliki font yang disematkan, sehingga font khusus ini, jika dikembalikan oleh metode Viewer.getAllFonts(), dipasang di sistem operasi tempat GroupDocs.Viewer berjalan.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Nama keluarga font, tanpa gaya, tidak pernah null atau kosong. |
|
|  | [getStyle()](#getStyle--) | Gaya font ini — dapat berupa Regular, Bold, Italic, atau BoldItalic. |
|
|  | [isStrikeout()](#isStrikeout--) | Menunjukkan apakah font memiliki satu garis coret. |
|
|  | [isUnderline()](#isUnderline--) | Menunjukkan apakah font memiliki garis bawah. |
|
|  | [getColor()](#getColor--) | Warna font ini. |
|
|  | [getCharset()](#getCharset--) | Set karakter font ini. |
|
|  | [getContent()](#getContent--) | Konten font ini sebagai array byte. |
|
|  | [getFormat()](#getFormat--) | Format font ini. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Menyerialkan info font ini sebagai aturan @font-face dan menuliskannya ke penulis yang ditentukan. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nama keluarga font, tanpa gaya, tidak pernah null atau kosong.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gaya font ini — dapat berupa Regular, Bold, Italic, atau BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Menunjukkan apakah font memiliki satu garis coret.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Menunjukkan apakah font memiliki garis bawah.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Warna font ini.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Set karakter font ini.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Konten font ini sebagai array byte. Bisa bernilai null jika hanya metadata yang tersedia.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format font ini.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Menyerialkan info font ini sebagai aturan @font-face dan menuliskannya ke penulis yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | output | java.io.Writer | Perangkat untuk menulis data teks yang diserialkan. |
|

