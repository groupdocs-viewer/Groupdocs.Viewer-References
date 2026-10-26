---
title: "FontStyles"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili 4 gaya kemungkinan font yang digunakan dalam dokumen Regular, Bold, Italic, atau Bold Italic."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Mewakili 4 gaya font yang mungkin, digunakan dalam dokumen: Regular, Bold, Italic, atau Bold Italic.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Membuat instance FontStyles dari flag bold/italic. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [toString(int style)](#toString-int-) | Mengonversi nilai gaya menjadi string yang dapat dibaca manusia. |
| [getName()](#getName--) | Mengembalikan nama yang dapat dibaca dari gaya font ini. |
| [isBold()](#isBold--) | Mengembalikan true jika bit tebal diatur. |
| [isItalic()](#isItalic--) | Mengembalikan true jika bit miring diatur. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Gabungan (C\# operator +) |
| [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Selisih (C\# operator -) |
| [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Mengurai nama gaya font menjadi FontStyles. |
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Membuat instance FontStyles dari flag bold/italic.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


Mengonversi nilai gaya menjadi string yang dapat dibaca manusia.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gaya | int | nilai gaya font |

**Returns:**
java.lang.String - representasi string dari gaya font
### getName() {#getName--}
```
public String getName()
```


Mengembalikan nama yang dapat dibaca dari gaya font ini.

**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Mengembalikan true jika bit tebal diatur.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Mengembalikan true jika bit miring diatur.

**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


Gabungan (C\# operator +)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pertama | com.groupdocs.viewer.fonts.FontStyles |  |
| kedua | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Selisih (C\# operator -)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| minuend | com.groupdocs.viewer.fonts.FontStyles |  |
| subtrahend | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Mengurai nama gaya font menjadi FontStyles.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gaya | java.lang.String |  |
| diurai | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true bila berhasil, false jika tidak.
