---
title: "FontFormat"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "UsedFontInfo sınıfında bulunabilecek tüm yazı tipi formatlarını temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

UsedFontInfo sınıfında bulunabilecek tüm yazı tipi formatlarını temsil eder.
## Fields

| Field | Açıklama |
| --- | --- |
| [Unknown](#Unknown) | Bilinmeyen veya geçersiz yazı tipi formatı. |
| [TrueType](#TrueType) | TrueType yazı tipi formatı (TTF). |
| [OpenType](#OpenType) | OpenType yazı tipi formatı (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection yazı tipi formatı (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType yazı tipi formatı (EOT). |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [toString(int format)](#toString-int-) | Bir format değerini insan tarafından okunabilir bir dizeye dönüştürür. |
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


Embedded OpenType yazı tipi formatı (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Bir format değerini insan tarafından okunabilir bir dizeye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | int | yazı tipi formatı değeri |

**Returns:**
java.lang.String - yazı tipi formatının dize temsili
