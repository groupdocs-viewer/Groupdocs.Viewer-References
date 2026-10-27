---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Viewer örneğine yüklenmiş bir Presentation belgesinde kullanılan bir fontun meta verilerini ve ikili verilerini kapsüller."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Viewer örneğine yüklenmiş bir Presentation belgesinde kullanılan bir fontun meta verilerini ve ikili verilerini kapsüller. Bu font, belge içeriğinde kullanılır ve belgenin içinde gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Font aile adını alır (hiç null veya boş değildir). |
| [getStyle()](#getStyle--) | Fontun stilini alır: Regular, Bold, Italic veya BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Bu fontun Viewer örneğine yüklenen belge içinde gömülü olup olmadığını gösterir. |
| [getFormat()](#getFormat--) | Fontun formatını alır (TrueType, OpenType, vb.). |
| [getContent()](#getContent--) | Fontun ikili içeriğini alır, yoksa font verisi mevcut değilse null. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu font bilgisini belirtilen yazar kullanılarak CSS @font-face kuralına serileştirir. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Font aile adını alır (hiç null veya boş değildir).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Fontun stilini alır: Regular, Bold, Italic veya BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Bu fontun Viewer örneğine yüklenen belge içinde gömülü olup olmadığını gösterir. Not: Spreadsheet belgeleri gömülü font içeremez, bu yüzden onlar için her zaman false döndürür.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Fontun formatını alır (TrueType, OpenType, vb.). Sadece meta veri mevcutsa, FontFormat.Unknown döndürür.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Fontun ikili içeriğini alır, yoksa font verisi mevcut değilse null.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu font bilgisini belirtilen yazar kullanılarak CSS @font-face kuralına serileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer | CSS'i yazmak için yazar (null olmamalıdır) |

