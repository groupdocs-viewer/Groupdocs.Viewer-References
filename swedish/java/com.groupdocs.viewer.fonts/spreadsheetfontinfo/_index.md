---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Inkapslar metainformation och binär data för ett teckensnitt från kalkylbladsdokumentet som har laddats in i Viewer-instansen."
type: docs
weight: 16
url: /sv/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Inkapslar metainformation och binär data för ett teckensnitt från kalkylbladsdokumentet, laddat in i Viewer-instansen. Kalkylbladsdokument kan inte ha inbäddade teckensnitt, så detta specifika teckensnitt, om det returneras av metoden Viewer.getAllFonts(), är installerat i operativsystemet där GroupDocs.Viewer körs.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Familjenamn för teckensnittet, utan stil, får aldrig vara null eller tomt. |
|
|  | [getStyle()](#getStyle--) | Stil för detta teckensnitt — kan vara Regular, Bold, Italic eller BoldItalic. |
|
|  | [isStrikeout()](#isStrikeout--) | Indikerar om teckensnittet har en enkel genomstrykning. |
|
|  | [isUnderline()](#isUnderline--) | Indikerar om teckensnittet har en understrykning. |
|
|  | [getColor()](#getColor--) | Färg på detta teckensnitt. |
|
|  | [getCharset()](#getCharset--) | Teckenuppsättning för detta teckensnitt. |
|
|  | [getContent()](#getContent--) | Innehåll för detta teckensnitt som en byte-array. |
|
|  | [getFormat()](#getFormat--) | Format för detta teckensnitt. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna teckensnittsinformation som en @font-face-atregel och skriver den till den angivna skrivaren. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familjenamn för teckensnittet, utan stil, får aldrig vara null eller tomt.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil för detta teckensnitt — kan vara Regular, Bold, Italic eller BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indikerar om teckensnittet har en enkel genomstrykning.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indikerar om teckensnittet har en understrykning.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Färg på detta teckensnitt.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Teckenuppsättning för detta teckensnitt.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Innehåll för detta teckensnitt som en byte-array. Kan vara null om endast metainformation finns tillgänglig.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format för detta teckensnitt.


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
|  | utdata | java.io.Writer | Enhet för att skriva serialiserad textdata i. |
|

