---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Viewer örneğine yüklenen bir Presentation belgesinde kullanılan bir yazı tipinin üst verilerini ve ikili verilerini kapsüller."
type: docs
weight: 15
url: /tr/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Viewer örneğine yüklenen bir Presentation belgesinde kullanılan bir yazı tipinin üst verilerini ve ikili verilerini kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgeye gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Yazı tipi aile adını alır (asla null veya boş değildir). |
|
|  | [getStyle()](#getStyle--) | Yazı tipinin stilini alır: Regular, Bold, Italic veya BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Bu yazı tipinin Viewer örneğine yüklenen belge içinde gömülü olup olmadığını gösterir. |
|
|  | [getFormat()](#getFormat--) | Yazı tipinin biçimini alır (TrueType, OpenType vb.). |
|
|  | [getContent()](#getContent--) | Yazı tipinin ikili içeriğini alır, ya da veri mevcut değilse null döndürür. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu yazı tipi bilgisini belirtilen yazıcıyı kullanarak CSS @font-face kuralına serileştirir. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Yazı tipi aile adını alır (asla null veya boş değildir).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Yazı tipinin stilini alır: Regular, Bold, Italic veya BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Bu yazı tipinin Viewer örneğine yüklenen belge içinde gömülü olup olmadığını gösterir. Not: Spreadsheet belgeleri gömülü yazı tipleri içeremez, bu nedenle bu değer her zaman false döner.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Yazı tipinin biçimini alır (TrueType, OpenType vb.). Yalnızca üst veri mevcutsa, FontFormat.Unknown döndürür.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Yazı tipinin ikili içeriğini alır, ya da veri mevcut değilse null döndürür.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu yazı tipi bilgisini belirtilen yazıcıyı kullanarak CSS @font-face kuralına serileştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | çıktı | java.io.Writer | CSS'i yazacak yazıcı (null olmamalıdır). |
|

