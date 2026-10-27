---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "GroupDocs.Viewer aracılığıyla bir Kelime İşleme belgesinde kullanılan bir değiştirilmiş yazı tipinin meta verilerini ve ikili verilerini kapsüller."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

GroupDocs.Viewer aracılığıyla bir WordProcessing belgesinde kullanılan bir ikame fontun meta verilerini ve ikili verilerini kapsüller. Değiştirilemez sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Tüm alanları başlatmak için kurucu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | İkame fontun aile adını döndürür (asla null değildir). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Orijinal fontun aile adını döndürür (asla null değildir). |
| [getStyle()](#getStyle--) | Orijinal fontun stilini döndürür. |
| [getContent()](#getContent--) | İkame fontun ikili içeriğini döndürür (asla null değildir). |
| [getFormat()](#getFormat--) | İkame fontun font biçimini döndürür. |
| [toString()](#toString--) | Bu ikame fontu tanımlayan bir dize döndürür: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Eşitlik, orijinal aile, ikame aile ve stil temelinde belirlenir. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu fontu bir yardımcı yöntem kullanarak @font-face CSS kuralı olarak serileştir. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Tüm alanları başlatmak için kurucu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originalFamilyName | java.lang.String | Orijinal font adı (sistemde bulunamadı) |
| substitutedFamilyName | java.lang.String | İkame font adı (mevcut) |
| stil | com.groupdocs.viewer.fonts.FontStyles | Font stili (Regular, Bold, Italic, BoldItalic) |
| content | byte[] | İkame fontun ikili içeriği (asla null değildir) |
| format | int | Font biçimi (TrueType, OpenType, vb.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


İkame fontun aile adını döndürür (asla null değildir).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Orijinal fontun aile adını döndürür (asla null değildir).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Orijinal fontun stilini döndürür.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


İkame fontun ikili içeriğini döndürür (asla null değildir).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


İkame fontun font biçimini döndürür.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Bu ikame fontu tanımlayan bir dize döndürür: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Eşitlik, orijinal aile, ikame aile ve stil temelinde belirlenir. HashSet veya HashMap gibi C\# IEqualityComparer kullanımında gereklidir.

**Parameters:**
| Parametre | Tür | Açıklama |
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


Bu fontu bir yardımcı yöntem kullanarak @font-face CSS kuralı olarak serileştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer |  |

