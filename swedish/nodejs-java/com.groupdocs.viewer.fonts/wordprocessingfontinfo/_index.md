---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Inkapslar metainformation och binär data för ett teckensnitt från WordProcessing-dokumentet som laddats in i Viewer-instansen."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Inkapslar metainformation och binär data för ett teckensnitt från WordProcessing-dokumentet, som laddats in i Viewer-instansen. Detta teckensnitt används i dokumentets innehåll och är inbäddat i själva dokumentet eller är installerat i operativsystemet där GroupDocs.Viewer körs.

Oföränderlig klass. Dess instanser skapas och returneras av GroupDocs.Viewer offentliga API och bör normalt inte skapas av användaren. För detaljer, se dokumentationen: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Typsnittets familjenamn, utan stil, aldrig null eller tomt. |
| [getAltFamilyName()](#getAltFamilyName--) | Alternativt familjenamn för typsnittet. |
| [getStyle()](#getStyle--) | Stil för typsnittet \u2014 kan vara Regular, Bold, Italic eller BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Anger om detta typsnitt är inbäddat i dokumentet (true) eller ett systemtypsnitt (false). |
| [getFormat()](#getFormat--) | Format för detta typsnitt. |
| [getContent()](#getContent--) | Innehåll för detta typsnitt som en bytearray, eller null om det inte är tillgängligt. |
| [getCharset()](#getCharset--) | Teckenuppsättning för detta typsnitt. |
| [toString()](#toString--) | Returnerar felsökningsinformation om detta typsnitt i följande mall: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna typsnittsinformation som en @font-face CSS-regel och skriver den till den angivna skrivaren. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Typsnittets familjenamn, utan stil, aldrig null eller tomt.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Alternativt familjenamn för typsnittet. Om det saknas, returneras en tom sträng.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil för typsnittet \u2014 kan vara Regular, Bold, Italic eller BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Anger om detta typsnitt är inbäddat i dokumentet (true) eller ett systemtypsnitt (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format för detta typsnitt. Om det endast finns metainformation och binärt innehåll saknas, kan det returnera FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Innehåll för detta typsnitt som en bytearray, eller null om det inte är tillgängligt.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Teckenuppsättning för detta typsnitt.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returnerar felsökningsinformation om detta typsnitt i följande mall: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar denna typsnittsinformation som en @font-face CSS-regel och skriver den till den angivna skrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | java.io.Writer | Skrivare för att ta emot den serialiserade CSS:n. |

