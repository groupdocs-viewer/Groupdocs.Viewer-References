---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Omvat metadata en binaire gegevens van één vervangen lettertype dat wordt gebruikt in een WordProcessing-document via GroupDocs.Viewer."
type: docs
weight: 18
url: /nl/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Omsluit metadata en binaire gegevens van één vervangen lettertype dat wordt gebruikt in een WordProcessing-document via GroupDocs.Viewer. Onveranderlijke klasse.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Constructor om alle velden te initialiseren. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Retourneert de familienaam van het vervangen lettertype (nooit null). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Retourneert de familienaam van het originele lettertype (nooit null). |
|
|  | [getStyle()](#getStyle--) | Retourneert de stijl van het originele lettertype. |
|
|  | [getContent()](#getContent--) | Retourneert de binaire inhoud van het vervangen lettertype (nooit null). |
|
|  | [getFormat()](#getFormat--) | Retourneert het lettertypeformaat van het vervangen lettertype. |
|
|  | [toString()](#toString--) | Retourneert een string die dit vervangen lettertype beschrijft: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Gelijkheid gebaseerd op originele familie, vervangen familie en stijl. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiseer dit lettertype als een @font-face CSS-regel met behulp van een hulpprogrammamethode. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Constructor om alle velden te initialiseren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | De originele lettertype‑naam (niet gevonden op het systeem) |
|
|  | substitutedFamilyName | java.lang.String | De vervangen lettertype‑naam (beschikbaar) |
|
|  | stijl | com.groupdocs.viewer.fonts.FontStyles | Lettertype‑stijl (Regular, Bold, Italic, BoldItalic) |
|
|  | content | byte[] | Binaire inhoud van het vervangen lettertype (nooit null) |
|
|  | formaat | int | Lettertypeformaat (TrueType, OpenType, enz.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Retourneert de familienaam van het vervangen lettertype (nooit null).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Retourneert de familienaam van het originele lettertype (nooit null).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Retourneert de stijl van het originele lettertype.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Retourneert de binaire inhoud van het vervangen lettertype (nooit null).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Retourneert het lettertypeformaat van het vervangen lettertype.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die dit vervangen lettertype beschrijft: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gelijkheid gebaseerd op originele familie, vervangen familie en stijl. Vereist voor gebruik in HashSet of HashMap zoals C# IEqualityComparer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiseer dit lettertype als een @font-face CSS-regel met behulp van een hulpprogrammamethode.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| output | java.io.Writer |  |

