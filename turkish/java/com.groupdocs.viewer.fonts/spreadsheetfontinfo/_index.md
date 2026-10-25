---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Viewer örneğine yüklenen bir Spreadsheet belgesinden bir yazı tipinin üst verilerini ve ikili verilerini kapsüller."
type: docs
weight: 16
url: /tr/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer örneğine yüklenen bir Spreadsheet belgesinden bir yazı tipinin üst verilerini ve ikili verilerini kapsüller. Spreadsheet belgeleri gömülü yazı tiplerine sahip olamaz, bu nedenle Viewer.getAllFonts() yöntemi tarafından döndürülen bu belirli yazı tipi, GroupDocs.Viewer'ın çalıştığı işletim sistemine kuruludur.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Yazı tipinin stil içermeyen aile adı, hiçbir zaman null veya boş değildir. |
|
|  | [getStyle()](#getStyle--) | Bu yazı tipinin stili \u2014 Regular, Bold, Italic veya BoldItalic olabilir. |
|
|  | [isStrikeout()](#isStrikeout--) | Yazı tipinin tek bir üstü çizili olup olmadığını gösterir. |
|
|  | [isUnderline()](#isUnderline--) | Yazı tipinin altı çizili olup olmadığını gösterir. |
|
|  | [getColor()](#getColor--) | Bu yazı tipinin rengi. |
|
|  | [getCharset()](#getCharset--) | Bu yazı tipinin karakter kümesi. |
|
|  | [getContent()](#getContent--) | Bu yazı tipinin içeriği bir bayt dizisi olarak. |
|
|  | [getFormat()](#getFormat--) | Bu yazı tipinin formatı. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Bu yazı tipi bilgisini bir @font-face at-rule olarak serileştirir ve belirtilen yazıcıya yazar. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Yazı tipinin stil içermeyen aile adı, hiçbir zaman null veya boş değildir.


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
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Bu yazı tipinin karakter kümesi.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Bu yazı tipinin içeriği bir bayt dizisi olarak. Yalnızca meta bilgi mevcutsa null olabilir.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Bu yazı tipinin formatı.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Bu yazı tipi bilgisini bir @font-face at-rule olarak serileştirir ve belirtilen yazıcıya yazar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | çıktı | java.io.Writer | Serileştirilmiş metin verilerini yazmak için cihaz. |
|

