---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Kapselt Metadaten und Binärdaten einer ersetzten Schriftart, die in einem Textverarbeitungsdokument über GroupDocs.Viewer verwendet wird."
type: docs
weight: 18
url: /de/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Kapselt Metadaten und binäre Daten einer ersetzten Schrift, die in einem WordProcessing-Dokument über GroupDocs.Viewer verwendet wird. Unveränderliche Klasse.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Konstruktor zum Initialisieren aller Felder. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Gibt den Familiennamen der ersetzten Schrift zurück (niemals null). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Gibt den Familiennamen der ursprünglichen Schrift zurück (niemals null). |
|
|  | [getStyle()](#getStyle--) | Gibt den Stil der Originalschrift zurück. |
|
|  | [getContent()](#getContent--) | Gibt den Binärinhalt der ersetzten Schrift zurück (niemals null). |
|
|  | [getFormat()](#getFormat--) | Gibt das Schriftformat der ersetzten Schrift zurück. |
|
|  | [toString()](#toString--) | Gibt einen String zurück, der diese ersetzte Schrift beschreibt: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Gleichheit basierend auf Originalfamilie, ersetzter Familie und Stil. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schrift als @font-face CSS-Regel mithilfe einer Hilfsmethode. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Konstruktor zum Initialisieren aller Felder.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | Der Originalschriftname (nicht im System gefunden) |
|
|  | substitutedFamilyName | java.lang.String | Der ersetzte Schriftname (verfügbar) |
|
|  | Stil | com.groupdocs.viewer.fonts.FontStyles | Schriftstil (Regular, Bold, Italic, BoldItalic) |
|
|  | Inhalt | byte[] | Binärinhalt der ersetzten Schrift (niemals null) |
|
|  | Format | int | Schriftformat (TrueType, OpenType, usw.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gibt den Familiennamen der ersetzten Schrift zurück (niemals null).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Gibt den Familiennamen der ursprünglichen Schrift zurück (niemals null).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gibt den Stil der Originalschrift zurück.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Gibt den Binärinhalt der ersetzten Schrift zurück (niemals null).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Gibt das Schriftformat der ersetzten Schrift zurück.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese ersetzte Schrift beschreibt: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gleichheit basierend auf Originalfamilie, ersetzter Familie und Stil. Erforderlich für die Verwendung in HashSet oder HashMap wie C# IEqualityComparer.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolesch
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


Serialisiert diese Schrift als @font-face CSS-Regel mithilfe einer Hilfsmethode.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ausgabe | java.io.Writer |  |

