---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "GroupDocs.Viewer aracılığıyla bir Kelime İşleme belgesinde kullanılan bir ikame yazı tipinin meta verilerini ve ikili verilerini kapsüller."
type: docs
weight: 18
url: /tr/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

GroupDocs.Viewer aracılığıyla bir WordProcessing belgesinde kullanılan bir ikame yazı tipinin meta verilerini ve ikili verilerini kapsüller. Değiştirilemez sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Tüm alanları başlatan yapıcı. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | İkame yazı tipinin aile adını döndürür (asla null değildir). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Orijinal yazı tipinin aile adını döndürür (asla null değildir). |
|
|  | [getStyle()](#getStyle--) | Orijinal yazı tipinin stilini döndürür. |
|
|  | [getContent()](#getContent--) | İkame yazı tipinin ikili içeriğini döndürür (asla null değildir). |
|
|  | [getFormat()](#getFormat--) | İkame yazı tipinin yazı tipi formatını döndürür. |
|
|  | [toString()](#toString--) | Bu ikame yazı tipini tanımlayan bir dize döndürür: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Orijinal aile, değiştirilmiş aile ve stil temelinde eşitlik. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu fontu bir yardımcı yöntem kullanarak @font-face CSS kuralı olarak serileştirin. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Tüm alanları başlatan yapıcı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | Orijinal font adı (sistemde bulunamadı) |
|
|  | substitutedFamilyName | java.lang.String | Değiştirilmiş font adı (mevcut) |
|
|  | stil | com.groupdocs.viewer.fonts.FontStyles | Font stili (Regular, Bold, Italic, BoldItalic) |
|
|  | içerik | byte[] | Değiştirilmiş fontun ikili içeriği (asla null değildir) |
|
|  | biçim | int | Font formatı (TrueType, OpenType, vb.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


İkame yazı tipinin aile adını döndürür (asla null değildir).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Orijinal yazı tipinin aile adını döndürür (asla null değildir).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Orijinal yazı tipinin stilini döndürür.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


İkame yazı tipinin ikili içeriğini döndürür (asla null değildir).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


İkame yazı tipinin yazı tipi formatını döndürür.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Bu ikame yazı tipini tanımlayan bir dize döndürür: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Orijinal aile, değiştirilmiş aile ve stil temelinde eşitlik. C# IEqualityComparer gibi HashSet veya HashMap kullanımında gereklidir.


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


Bu fontu bir yardımcı yöntem kullanarak @font-face CSS kuralı olarak serileştirin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer |  |

