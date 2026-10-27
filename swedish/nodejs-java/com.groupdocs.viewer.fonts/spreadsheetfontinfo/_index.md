---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Innesluter metainformation och binär data för ett teckensnitt från Spreadsheet-dokumentet som laddats in i Viewer-instansen."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Innesluter metainformation och binär data för ett teckensnitt från Spreadsheet-dokumentet, som laddats in i Viewer-instansen. Spreadsheet-dokument kan inte ha inbäddade teckensnitt, så detta specifika teckensnitt, om det returneras av Viewer.getAllFonts()-metoden, är installerat i operativsystemet där GroupDocs.Viewer körs.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Typsnittets familjenamn, utan stil, aldrig null eller tomt. |
| [getStyle()](#getStyle--) | Stil för detta teckensnitt \u2014 kan vara Regular, Bold, Italic eller BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Anger om teckensnittet har en enkel genomstrykning. |
| [isUnderline()](#isUnderline--) | Anger om teckensnittet har en understrykning. |
| [getColor()](#getColor--) | Färg på detta teckensnitt. |
| [getCharset()](#getCharset--) | Teckenuppsättning för detta typsnitt. |
| [getContent()](#getContent--) | Innehåll för detta teckensnitt som en bytearray. |
| [getFormat()](#getFormat--) | Format för detta typsnitt. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna teckensnittsinformation som en @font-face-atregel och skriver den till den angivna skrivaren. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Typsnittets familjenamn, utan stil, aldrig null eller tomt.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil för detta teckensnitt \u2014 kan vara Regular, Bold, Italic eller BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Anger om teckensnittet har en enkel genomstrykning.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Anger om teckensnittet har en understrykning.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Färg på detta teckensnitt.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Teckenuppsättning för detta typsnitt.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Innehåll för detta teckensnitt som en bytearray. Kan vara null om endast metainformation är tillgänglig.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format för detta typsnitt.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar denna teckensnittsinformation som en @font-face-atregel och skriver den till den angivna skrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | java.io.Writer | Enhet att skriva serialiserad textdata till. |

