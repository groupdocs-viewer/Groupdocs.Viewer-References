---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Innesluter metadata och binär data för ett teckensnitt från ett PDF-dokument som laddats in i Viewer-instansen."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Inkapslar meta-information och binär data för ett typsnitt från ett PDF-dokument, laddat i Viewer-instansen.

Detta teckensnitt används i dokumentinnehållet och är antingen:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Intern konstruktor som används vid PDF-teckensnittsextraktion. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Hämtar teckensnittsfamiljens namn. |
| [getStyle()](#getStyle--) | Hämtar stilen för detta teckensnitt. |
| [isEmbedded()](#isEmbedded--) | Returnerar om teckensnittet är inbäddat i PDF-dokumentet. |
| [isInstalled()](#isInstalled--) | Returnerar om teckensnittet är installerat i operativsystemet. |
| [getFormat()](#getFormat--) | Returnerar filformatet för teckensnittet. |
| [getContent()](#getContent--) | Returnerar det binära innehållet för teckensnittet. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar detta teckensnitt som en CSS @font-face-regel. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Intern konstruktor som används vid PDF-teckensnittsextraktion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| familyName | java.lang.String | namn på teckensnittsfamilj |
| stil | com.groupdocs.viewer.fonts.FontStyles | stil (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true om teckensnittet är inbäddat i PDF |
| isInstalled | boolean | true om teckensnittet är installerat i operativsystemet |
| content | byte[] | binära teckensnittsdata (nullbar) |
| format | int | teckensnittsfilformat |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Hämtar teckensnittsfamiljens namn.

**Returns:**
java.lang.String - sträng för familjenamn (aldrig null eller tom)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Hämtar stilen för detta teckensnitt.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - teckensnittsstilen
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Returnerar om teckensnittet är inbäddat i PDF-dokumentet.

**Returns:**
boolean - true om inbäddat
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Returnerar om teckensnittet är installerat i operativsystemet.

**Returns:**
boolean - true om installerad
### getFormat() {#getFormat--}
```
public int getFormat()
```


Returnerar filformatet för teckensnittet.

**Returns:**
int - teckensnittets formatenum
### getContent() {#getContent--}
```
public byte[] getContent()
```


Returnerar det binära innehållet för teckensnittet.

**Returns:**
byte[] - bytearray eller null om ej tillgänglig
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar detta teckensnitt som en CSS @font-face-regel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | java.io.Writer | skrivare som CSS kommer att skrivas till |

