---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Viewer örneğine yüklenen bir PDF belgesinden bir yazı tipinin meta‑bilgilerini ve ikili verilerini kapsüller."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Viewer örneğine yüklenen bir PDF belgesinden bir yazı tipinin meta‑bilgilerini ve ikili verilerini kapsüller.

Bu yazı tipi belge içeriğinde kullanılır ve şu şekillerden biridir:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF yazı tipi çıkarımı tarafından kullanılan dahili yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Yazı tipi ailesi adını alır. |
| [getStyle()](#getStyle--) | Bu yazı tipinin stilini alır. |
| [isEmbedded()](#isEmbedded--) | Yazı tipinin PDF belgesi içinde gömülü olup olmadığını döndürür. |
| [isInstalled()](#isInstalled--) | Yazı tipinin işletim sistemine kurulu olup olmadığını döndürür. |
| [getFormat()](#getFormat--) | Yazı tipinin dosya formatını döndürür. |
| [getContent()](#getContent--) | Yazı tipinin ikili içeriğini döndürür. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu yazı tipini bir CSS @font-face kuralı olarak serileştirir. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF yazı tipi çıkarımı tarafından kullanılan dahili yapıcı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| familyName | java.lang.String | yazı tipi ailesi adı |
| stil | com.groupdocs.viewer.fonts.FontStyles | stil (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true eğer yazı tipi PDF içinde gömülü ise |
| isInstalled | boolean | true eğer yazı tipi işletim sistemine kurulu ise |
| content | byte[] | ikili yazı tipi verisi (nullable) |
| format | int | yazı tipi dosya formatı |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Yazı tipi ailesi adını alır.

**Returns:**
java.lang.String - aile adı dizesi (asla null veya boş değildir)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Bu yazı tipinin stilini alır.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - yazı tipi stili
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Yazı tipinin PDF belgesi içinde gömülü olup olmadığını döndürür.

**Returns:**
boolean - gömülü ise true
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Yazı tipinin işletim sistemine kurulu olup olmadığını döndürür.

**Returns:**
boolean - kurulu ise true
### getFormat() {#getFormat--}
```
public int getFormat()
```


Yazı tipinin dosya formatını döndürür.

**Returns:**
int - yazı tipi formatı enumu
### getContent() {#getContent--}
```
public byte[] getContent()
```


Yazı tipinin ikili içeriğini döndürür.

**Returns:**
byte[] - bayt dizisi veya mevcut değilse null
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu yazı tipini bir CSS @font-face kuralı olarak serileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer | CSS'in yazılacağı writer |

