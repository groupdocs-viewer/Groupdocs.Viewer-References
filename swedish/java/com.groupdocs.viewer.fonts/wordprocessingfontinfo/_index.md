---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Inkapslar metainformation och binär data för ett teckensnitt från WordProcessing‑dokumentet som laddats in i Viewer‑instansen."
type: docs
weight: 17
url: /sv/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Inkapslar metainformation och binär data för ett teckensnitt från WordProcessing‑dokumentet, som laddats in i Viewer‑instansen. Detta teckensnitt används i dokumentets innehåll och är inbäddat i själva dokumentet eller är installerat i operativsystemet där GroupDocs.Viewer körs.

Oföränderlig klass. Dess instanser skapas och returneras av GroupDocs.Viewer
offentligt API och bör normalt inte skapas av användaren.
För detaljer, se dokumentationen:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Familjenamn för teckensnittet, utan stil, får aldrig vara null eller tomt. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Alternativt familjenamn för teckensnittet. |
|
|  | [getStyle()](#getStyle--) | Stil för teckensnittet \\u2014 kan vara Regular, Bold, Italic eller BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Anger om detta teckensnitt är inbäddat i dokumentet (true) eller ett systemteckensnitt (false). |
|
|  | [getFormat()](#getFormat--) | Format för detta teckensnitt. |
|
|  | [getContent()](#getContent--) | Innehåll för detta teckensnitt som en byte‑array, eller null om det inte är tillgängligt. |
|
|  | [getCharset()](#getCharset--) | Teckenuppsättning för detta teckensnitt. |
|
|  | [toString()](#toString--) | Returnerar felsökningsinformation om detta teckensnitt i följande mall: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna teckensnittsinfo som en @font-face CSS‑regel och skriver den till den angivna skrivaren. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familjenamn för teckensnittet, utan stil, får aldrig vara null eller tomt.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Alternativt familjenamn för teckensnittet. Om det saknas, returneras en tom sträng.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil för teckensnittet \\u2014 kan vara Regular, Bold, Italic eller BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Anger om detta teckensnitt är inbäddat i dokumentet (true) eller ett systemteckensnitt (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format för detta teckensnitt. Om det bara finns metainformation och binärt innehåll saknas, kan det returnera FontFormat.UNKNOWN.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Innehåll för detta teckensnitt som en byte‑array, eller null om det inte är tillgängligt.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Teckenuppsättning för detta teckensnitt.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returnerar felsökningsinformation om detta teckensnitt i följande mall: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar denna teckensnittsinfo som en @font-face CSS‑regel och skriver den till den angivna skrivaren.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | utdata | java.io.Writer | Skrivare för att ta emot den serialiserade CSS:n. |
|

