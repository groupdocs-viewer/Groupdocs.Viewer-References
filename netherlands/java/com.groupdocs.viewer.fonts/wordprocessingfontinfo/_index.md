---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Omsluit metagegevens en binaire gegevens van één lettertype uit het WordProcessing-document dat is geladen in de Viewer‑instantie."
type: docs
weight: 17
url: /nl/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Omsluit metagegevens en binaire gegevens van één lettertype uit het WordProcessing-document, geladen in de Viewer‑instantie. Dit lettertype wordt gebruikt in de documentinhoud en is ingebed in het document zelf of geïnstalleerd in het besturingssysteem waarop GroupDocs.Viewer draait.

Immutable klasse. Zijn instanties worden geproduceerd en geretourneerd door de GroupDocs.Viewer
publieke API en zou normaal gesproken niet door de gebruiker moeten worden aangemaakt.
Voor details, zie de documentatie:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Familienaam van het lettertype, zonder stijl, nooit null of leeg. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Alternatieve familienaam van het lettertype. |
|
|  | [getStyle()](#getStyle--) | Stijl van het lettertype \\u2014 kan Regular, Bold, Italic of BoldItalic zijn. |
|
|  | [isEmbedded()](#isEmbedded--) | Geeft aan of dit lettertype is ingesloten in het document (true) of een systeembreed lettertype (false). |
|
|  | [getFormat()](#getFormat--) | Formaat van dit lettertype. |
|
|  | [getContent()](#getContent--) | Inhoud van dit lettertype als een byte‑array, of null indien niet beschikbaar. |
|
|  | [getCharset()](#getCharset--) | Karakterset van dit lettertype. |
|
|  | [toString()](#toString--) | Retourneert debug‑informatie over dit lettertype in het volgende sjabloon: "naam stijl, ingesloten/systeem, formaat" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiseert deze lettertype‑informatie als een @font-face CSS‑regel en schrijft deze naar de opgegeven writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familienaam van het lettertype, zonder stijl, nooit null of leeg.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Alternatieve familienaam van het lettertype. Indien afwezig, wordt een lege string geretourneerd.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stijl van het lettertype \\u2014 kan Regular, Bold, Italic of BoldItalic zijn.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Geeft aan of dit lettertype is ingesloten in het document (true) of een systeembreed lettertype (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formaat van dit lettertype. Als er alleen metagegevens zijn en de binaire inhoud ontbreekt, kan FontFormat.UNKNOWN worden geretourneerd.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Inhoud van dit lettertype als een byte‑array, of null indien niet beschikbaar.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Karakterset van dit lettertype.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Retourneert debug‑informatie over dit lettertype in het volgende sjabloon: "naam stijl, ingesloten/systeem, formaat"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiseert deze lettertype‑informatie als een @font-face CSS‑regel en schrijft deze naar de opgegeven writer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | output | java.io.Writer | Writer om de geserialiseerde CSS te ontvangen. |
|

