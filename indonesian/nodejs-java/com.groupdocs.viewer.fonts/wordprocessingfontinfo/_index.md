---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mengkapsulkan metainfo dan data biner dari satu font dalam dokumen WordProcessing yang dimuat ke dalam instance Viewer."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Menyatukan metainfo dan data biner dari satu font dari dokumen WordProcessing, yang dimuat ke dalam instance Viewer. Font ini digunakan dalam konten dokumen dan disematkan di dalam dokumen itu sendiri atau diinstal di sistem operasi tempat GroupDocs.Viewer berjalan.

Kelas tidak dapat diubah. Instansinya diproduksi dan dikembalikan oleh API publik GroupDocs.Viewer dan biasanya tidak boleh dibuat oleh pengguna. Untuk detail, lihat dokumentasi: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nama keluarga font, tanpa gaya, tidak pernah null atau kosong. |
| [getAltFamilyName()](#getAltFamilyName--) | Nama keluarga alternatif font. |
| [getStyle()](#getStyle--) | Gaya font \\u2014 dapat berupa Regular, Bold, Italic, atau BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Menunjukkan apakah font ini disematkan di dalam dokumen (true) atau merupakan font sistem (false). |
| [getFormat()](#getFormat--) | Format font ini. |
| [getContent()](#getContent--) | Konten font ini sebagai array byte, atau null jika tidak tersedia. |
| [getCharset()](#getCharset--) | Set karakter font ini. |
| [toString()](#toString--) | Mengembalikan info debug tentang font ini dalam templat berikut: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Menyerialkan info font ini sebagai aturan CSS @font-face dan menuliskannya ke penulis yang ditentukan. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nama keluarga font, tanpa gaya, tidak pernah null atau kosong.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Nama keluarga alternatif font. Jika tidak ada, mengembalikan string kosong.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gaya font \\u2014 dapat berupa Regular, Bold, Italic, atau BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Menunjukkan apakah font ini disematkan di dalam dokumen (true) atau merupakan font sistem (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format font ini. Jika hanya ada metainfo dan konten biner tidak ada, dapat mengembalikan FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Konten font ini sebagai array byte, atau null jika tidak tersedia.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Set karakter font ini.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Mengembalikan info debug tentang font ini dalam templat berikut: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Menyerialkan info font ini sebagai aturan CSS @font-face dan menuliskannya ke penulis yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keluaran | java.io.Writer | Penulis untuk menerima CSS yang diserialkan. |

