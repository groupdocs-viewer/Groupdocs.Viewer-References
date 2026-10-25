---
title: "FontFormat"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "KullanılanFontInfo sınıfında bulunabilecek tüm yazı tipi formatlarını temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

UsedFontInfo sınıfında bulunabilecek tüm yazı tipi formatlarını temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Unknown](#Unknown) | Bilinmeyen veya geçersiz yazı tipi formatı. |
|
|  | [TrueType](#TrueType) | TrueType yazı tipi formatı (TTF). |
|
|  | [OpenType](#OpenType) | OpenType yazı tipi formatı (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection yazı tipi formatı (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Gömülü OpenType yazı tipi formatı (EOT). |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Bir format değerini insan tarafından okunabilir bir dizeye dönüştürür. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Bilinmeyen veya geçersiz yazı tipi formatı.


### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType yazı tipi formatı (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType yazı tipi formatı (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection yazı tipi formatı (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Gömülü OpenType yazı tipi formatı (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Bir format değerini insan tarafından okunabilir bir dizeye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | biçim | int | yazı tipi formatı değeri |
|

**Returns:**
java.lang.String - yazı tipi formatının dize temsili

