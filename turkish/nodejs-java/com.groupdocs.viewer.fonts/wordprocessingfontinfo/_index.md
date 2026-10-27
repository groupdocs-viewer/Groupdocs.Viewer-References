---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Viewer örneğine yüklenen WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verisini kapsüller."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

WordProcessing belgesinden bir fontun meta bilgilerini ve ikili verilerini, Viewer örneğine yüklenmiş şekilde kapsüller. Bu font, belge içeriğinde kullanılır ve belgenin içinde gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir.

Değiştirilemez sınıf. Örnekleri GroupDocs.Viewer genel API'si tarafından üretilir ve döndürülür ve normalde kullanıcı tarafından oluşturulmamalıdır. Ayrıntılar için belgeleri inceleyin: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Fontun aile adı, stil olmadan, hiçbir zaman null veya boş değildir. |
| [getAltFamilyName()](#getAltFamilyName--) | Fontun alternatif aile adı. |
| [getStyle()](#getStyle--) | Fontun stili — Regular, Bold, Italic veya BoldItalic olabilir. |
| [isEmbedded()](#isEmbedded--) | Bu fontun belge içinde gömülü olup olmadığını (true) veya sistem fontu (false) olduğunu gösterir. |
| [getFormat()](#getFormat--) | Bu fontun formatı. |
| [getContent()](#getContent--) | Bu fontun içeriği bayt dizisi olarak, yoksa null. |
| [getCharset()](#getCharset--) | Bu fontun karakter seti. |
| [toString()](#toString--) | Bu font hakkında hata ayıklama bilgilerini aşağıdaki şablonda döndürür: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu font bilgisini @font-face CSS kuralı olarak serileştirir ve belirtilen yazıcıya yazar. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Fontun aile adı, stil olmadan, hiçbir zaman null veya boş değildir.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Fontun alternatif aile adı. Eksikse, boş string döndürür.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Fontun stili — Regular, Bold, Italic veya BoldItalic olabilir.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Bu fontun belge içinde gömülü olup olmadığını (true) veya sistem fontu (false) olduğunu gösterir.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Bu fontun formatı. Sadece meta bilgi mevcut ve ikili içerik eksikse, FontFormat.UNKNOWN döndürebilir.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Bu fontun içeriği bayt dizisi olarak, yoksa null.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Bu fontun karakter seti.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Bu font hakkında hata ayıklama bilgilerini aşağıdaki şablonda döndürür: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu font bilgisini @font-face CSS kuralı olarak serileştirir ve belirtilen yazıcıya yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer | Serileştirilmiş CSS'i alacak yazar. |

