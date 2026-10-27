---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Görüntüleyici örneğine yüklenen Spreadsheet belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Görüntüleyici örneğine yüklenen Spreadsheet belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller. Spreadsheet belgelerinde gömülü yazı tipleri bulunamaz, bu nedenle Viewer.getAllFonts() yöntemiyle döndürülen bu belirli yazı tipi, GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulur.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Fontun aile adı, stil olmadan, hiçbir zaman null veya boş değildir. |
| [getStyle()](#getStyle--) | Bu yazı tipinin stili \u2014 Regular, Bold, Italic veya BoldItalic olabilir. |
| [isStrikeout()](#isStrikeout--) | Yazı tipinin tek bir üstü çizili olup olmadığını gösterir. |
| [isUnderline()](#isUnderline--) | Yazı tipinin altı çizili olup olmadığını gösterir. |
| [getColor()](#getColor--) | Bu yazı tipinin rengi. |
| [getCharset()](#getCharset--) | Bu fontun karakter seti. |
| [getContent()](#getContent--) | Bu yazı tipinin içeriği bayt dizisi olarak. |
| [getFormat()](#getFormat--) | Bu fontun formatı. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen yazara yazar. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Fontun aile adı, stil olmadan, hiçbir zaman null veya boş değildir.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Bu yazı tipinin stili \u2014 Regular, Bold, Italic veya BoldItalic olabilir.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Yazı tipinin tek bir üstü çizili olup olmadığını gösterir.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Yazı tipinin altı çizili olup olmadığını gösterir.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Bu yazı tipinin rengi.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Bu fontun karakter seti.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca meta bilgi mevcutsa null olabilir.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Bu fontun formatı.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu yazı tipi bilgisini @font-face at-rule olarak serileştirir ve belirtilen yazara yazar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıktı | java.io.Writer | Serileştirilmiş metin verilerini yazmak için cihaz. |

