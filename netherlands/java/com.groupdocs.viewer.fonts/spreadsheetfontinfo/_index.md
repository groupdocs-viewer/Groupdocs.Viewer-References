---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Omsluit metagegevens en binaire gegevens van één lettertype uit het Spreadsheet‑document dat in de Viewer‑instantie is geladen."
type: docs
weight: 16
url: /nl/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Omsluit metagegevens en binaire gegevens van één lettertype uit het Spreadsheet‑document, geladen in de Viewer‑instantie. Spreadsheet‑documenten kunnen geen ingebedde lettertypen bevatten, dus dit specifieke lettertype, indien geretourneerd door de Viewer.getAllFonts()‑methode, is geïnstalleerd in het besturingssysteem waarop GroupDocs.Viewer draait.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Familienaam van het lettertype, zonder stijl, nooit null of leeg. |
|
|  | [getStyle()](#getStyle--) | Stijl van dit lettertype \\u2014 kan Regular, Bold, Italic of BoldItalic zijn. |
|
|  | [isStrikeout()](#isStrikeout--) | Geeft aan of het lettertype een enkele doorhaling heeft. |
|
|  | [isUnderline()](#isUnderline--) | Geeft aan of het lettertype onderstreept is. |
|
|  | [getColor()](#getColor--) | Kleur van dit lettertype. |
|
|  | [getCharset()](#getCharset--) | Karakterset van dit lettertype. |
|
|  | [getContent()](#getContent--) | Inhoud van dit lettertype als een byte‑array. |
|
|  | [getFormat()](#getFormat--) | Formaat van dit lettertype. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiseert deze lettertype‑informatie als een @font-face‑at‑rule en schrijft deze naar de opgegeven writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familienaam van het lettertype, zonder stijl, nooit null of leeg.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stijl van dit lettertype \\u2014 kan Regular, Bold, Italic of BoldItalic zijn.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Geeft aan of het lettertype een enkele doorhaling heeft.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Geeft aan of het lettertype onderstreept is.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Kleur van dit lettertype.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Karakterset van dit lettertype.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Inhoud van dit lettertype als een byte‑array. Kan null zijn als alleen metagegevens beschikbaar zijn.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formaat van dit lettertype.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiseert deze lettertype‑informatie als een @font-face‑at‑rule en schrijft deze naar de opgegeven writer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | output | java.io.Writer | Apparaat om geserialiseerde tekstgegevens naar toe te schrijven. |
|

