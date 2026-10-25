---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Inkapslar metadata och binär data för ett teckensnitt som används i ett Presentation-dokument som har laddats in i Viewer-instansen."
type: docs
weight: 15
url: /sv/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Inkapslar metadata och binär data för ett teckensnitt som används i ett Presentation-dokument, laddat in i Viewer-instansen. Detta teckensnitt används i dokumentets innehåll och kan vara inbäddat i själva dokumentet eller installerat i operativsystemet där GroupDocs.Viewer körs.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Hämtar teckensnittsfamiljens namn (aldrig null eller tomt). |
|
|  | [getStyle()](#getStyle--) | Hämtar teckensnittets stil: Regular, Bold, Italic eller BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indikerar om detta teckensnitt är inbäddat i dokumentet som har laddats in i Viewer-instansen. |
|
|  | [getFormat()](#getFormat--) | Hämtar teckensnittets format (TrueType, OpenType osv.). |
|
|  | [getContent()](#getContent--) | Hämtar den binära teckensnittsdata, eller null om teckensnittsdata saknas. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiserar denna teckensnittsinformation till CSS @font-face-regel med den angivna skrivaren. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Hämtar teckensnittsfamiljens namn (aldrig null eller tomt).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Hämtar teckensnittets stil: Regular, Bold, Italic eller BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indikerar om detta teckensnitt är inbäddat i dokumentet som har laddats in i Viewer-instansen. Obs: Kalkylbladsdokument kan inte innehålla inbäddade teckensnitt, så för dem returneras alltid false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Hämtar teckensnittets format (TrueType, OpenType osv.). Om endast metadata finns tillgänglig, returneras FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Hämtar den binära teckensnittsdata, eller null om teckensnittsdata saknas.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiserar denna teckensnittsinformation till CSS @font-face-regel med den angivna skrivaren.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | utdata | java.io.Writer | skrivare för att skriva CSS i (får inte vara null) |
|

