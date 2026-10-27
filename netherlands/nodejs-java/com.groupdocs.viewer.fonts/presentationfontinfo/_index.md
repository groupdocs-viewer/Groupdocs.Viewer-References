---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Omsluit metadata en binaire gegevens van een lettertype dat wordt gebruikt in een Presentation‑document geladen in de Viewer‑instantie."
type: docs
weight: 15
url: /nl/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Omsluit metadata en binaire gegevens van een lettertype dat wordt gebruikt in een Presentation‑document, geladen in de Viewer‑instantie. Dit lettertype wordt gebruikt in de documentinhoud en kan ingebed zijn in het document zelf of geïnstalleerd in het besturingssysteem waarop GroupDocs.Viewer draait.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Haalt de familienaam van het lettertype op (nooit null of leeg). |
| [getStyle()](#getStyle--) | Haalt de stijl van het lettertype op: Regular, Bold, Italic of BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Geeft aan of dit lettertype is ingebed in het document dat is geladen in de Viewer‑instantie. |
| [getFormat()](#getFormat--) | Haalt het formaat van het lettertype op (TrueType, OpenType, enz.). |
| [getContent()](#getContent--) | Haalt de binaire inhoud van het lettertype op, of null als de lettertype‑gegevens niet beschikbaar zijn. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiseert deze lettertype‑informatie naar een CSS @font-face‑regel met behulp van de opgegeven writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Haalt de familienaam van het lettertype op (nooit null of leeg).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Haalt de stijl van het lettertype op: Regular, Bold, Italic of BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Geeft aan of dit lettertype is ingebed in het document dat is geladen in de Viewer‑instantie. Opmerking: Spreadsheet‑documenten kunnen geen ingebedde lettertypen bevatten, dus voor hen retourneert dit altijd false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Haalt het formaat van het lettertype op (TrueType, OpenType, enz.). Als alleen metadata beschikbaar is, wordt FontFormat.Unknown geretourneerd.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Haalt de binaire inhoud van het lettertype op, of null als de lettertype‑gegevens niet beschikbaar zijn.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiseert deze lettertype‑informatie naar een CSS @font-face‑regel met behulp van de opgegeven writer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uitvoer | java.io.Writer | schrijver om CSS in te schrijven (mag niet null zijn) |

