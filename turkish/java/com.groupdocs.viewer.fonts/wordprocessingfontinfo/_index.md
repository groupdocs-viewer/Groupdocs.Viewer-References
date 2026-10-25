---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Viewer örneğine yüklenen WordProcessing belgesindeki bir yazı tipinin meta bilgisini ve ikili verisini kapsüller."
type: docs
weight: 17
url: /tr/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Viewer örneğine yüklenen WordProcessing belgesindeki bir yazı tipinin meta bilgisini ve ikili verisini kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü ya da GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulu olur.

Değiştirilemez sınıf. Örnekleri GroupDocs.Viewer tarafından üretilir ve döndürülür.
public API ve normalde kullanıcı tarafından oluşturulmamalıdır.
Ayrıntılar için belgeleri inceleyin:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Yazı tipinin stil içermeyen aile adı, hiçbir zaman null veya boş değildir. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Yazı tipinin alternatif aile adı. |
|
|  | [getStyle()](#getStyle--) | Yazı tipinin stili \u2014 Regular, Bold, Italic veya BoldItalic olabilir. |
|
|  | [isEmbedded()](#isEmbedded--) | Bu yazı tipinin belge içinde gömülü (true) mi yoksa sistem yazı tipi (false) mi olduğunu gösterir. |
|
|  | [getFormat()](#getFormat--) | Bu yazı tipinin formatı. |
|
|  | [getContent()](#getContent--) | Bu yazı tipinin içeriği bayt dizisi olarak, bulunamazsa null. |
|
|  | [getCharset()](#getCharset--) | Bu yazı tipinin karakter kümesi. |
|
|  | [toString()](#toString--) | Bu yazı tipiyle ilgili hata ayıklama bilgilerini aşağıdaki şablonda döndürür: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu yazı tipi bilgisini bir @font-face CSS kuralı olarak serileştirir ve belirtilen yazıcıya yazar. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Yazı tipinin stil içermeyen aile adı, hiçbir zaman null veya boş değildir.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Yazı tipinin alternatif aile adı. Eksikse, boş dize döndürür.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Yazı tipinin stili \u2014 Regular, Bold, Italic veya BoldItalic olabilir.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Bu yazı tipinin belge içinde gömülü (true) mi yoksa sistem yazı tipi (false) mi olduğunu gösterir.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Bu yazı tipinin biçimi. Yalnızca üst veri varsa ve ikili içerik eksikse, FontFormat.UNKNOWN döndürebilir.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Bu yazı tipinin içeriği bayt dizisi olarak, bulunamazsa null.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Bu yazı tipinin karakter kümesi.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Bu yazı tipiyle ilgili hata ayıklama bilgilerini aşağıdaki şablonda döndürür: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu yazı tipi bilgisini bir @font-face CSS kuralı olarak serileştirir ve belirtilen yazıcıya yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | çıktı | java.io.Writer | Serileştirilmiş CSS'i alacak yazıcı. |
|

