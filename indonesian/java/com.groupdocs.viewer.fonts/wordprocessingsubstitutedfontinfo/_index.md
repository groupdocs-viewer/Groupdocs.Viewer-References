---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mengkapsulkan metadata dan data biner dari satu font substitusi yang digunakan dalam dokumen WordProcessing melalui GroupDocs.Viewer."
type: docs
weight: 18
url: /id/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Mengkapsulkan metadata dan data biner dari satu font yang digantikan yang digunakan dalam dokumen WordProcessing melalui GroupDocs.Viewer. Kelas tidak dapat diubah.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Konstruktor untuk menginisialisasi semua bidang. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Mengembalikan nama keluarga font yang digantikan (tidak pernah null). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Mengembalikan nama keluarga font asli (tidak pernah null). |
|
|  | [getStyle()](#getStyle--) | Mengembalikan gaya font asli. |
|
|  | [getContent()](#getContent--) | Mengembalikan konten biner font yang digantikan (tidak pernah null). |
|
|  | [getFormat()](#getFormat--) | Mengembalikan format font dari font yang digantikan. |
|
|  | [toString()](#toString--) | Mengembalikan string yang menggambarkan font yang digantikan ini: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Kesetaraan berdasarkan keluarga asli, keluarga yang digantikan, dan gaya. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisasikan font ini sebagai aturan CSS @font-face menggunakan metode utilitas. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Konstruktor untuk menginisialisasi semua bidang.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | Nama font asli (tidak ditemukan di sistem) |
|
|  | substitutedFamilyName | java.lang.String | Nama font yang digantikan (tersedia) |
|
|  | gaya | com.groupdocs.viewer.fonts.FontStyles | Gaya font (Regular, Bold, Italic, BoldItalic) |
|
|  | content | byte[] | Konten biner font yang digantikan (tidak pernah null) |
|
|  | format | int | Format font (TrueType, OpenType, dll.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Mengembalikan nama keluarga font yang digantikan (tidak pernah null).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Mengembalikan nama keluarga font asli (tidak pernah null).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Mengembalikan gaya font asli.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Mengembalikan konten biner font yang digantikan (tidak pernah null).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Mengembalikan format font dari font yang digantikan.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang menggambarkan font yang digantikan ini: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kesetaraan berdasarkan keluarga asli, keluarga yang digantikan, dan gaya. Diperlukan untuk penggunaan dalam HashSet atau HashMap seperti C# IEqualityComparer.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisasikan font ini sebagai aturan CSS @font-face menggunakan metode utilitas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | java.io.Writer |  |

