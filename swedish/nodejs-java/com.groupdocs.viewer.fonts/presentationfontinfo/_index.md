---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Inkapslar metadata och binär data för ett typsnitt som används i ett Presentation-dokument som laddats in i Viewer-instansen."
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Inkapslar metadata och binär data för ett typsnitt som används i ett Presentation-dokument, laddat in i Viewer-instansen. Detta typsnitt används i dokumentets innehåll och kan vara inbäddat i själva dokumentet eller installerat i operativsystemet där GroupDocs.Viewer körs.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Hämtar typsnittets familjenamn (aldrig null eller tomt). |
| [getStyle()](#getStyle--) | Hämtar typsnittets stil: Regular, Bold, Italic eller BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Anger om detta typsnitt är inbäddat i dokumentet som laddats in i Viewer-instansen. |
| [getFormat()](#getFormat--) | Hämtar typsnittets format (TrueType, OpenType, etc.). |
| [getContent()](#getContent--) | Hämtar det binära typsnittsinhållet, eller null om typsnittsdata inte är tillgängliga. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna typsnittsinformation till en CSS @font-face-regel med den angivna skrivaren. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Hämtar typsnittets familjenamn (aldrig null eller tomt).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Hämtar typsnittets stil: Regular, Bold, Italic eller BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Anger om detta typsnitt är inbäddat i dokumentet som laddats in i Viewer-instansen. Obs: Kalkylbladsdokument kan inte innehålla inbäddade typsnitt, så för dem returneras alltid false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Hämtar typsnittets format (TrueType, OpenType, etc.). Om endast metadata är tillgängliga, returneras FontFormat.Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Hämtar det binära typsnittsinhållet, eller null om typsnittsdata inte är tillgängliga.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar denna typsnittsinformation till en CSS @font-face-regel med den angivna skrivaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | java.io.Writer | skrivare för att skriva CSS i (får inte vara null) |

