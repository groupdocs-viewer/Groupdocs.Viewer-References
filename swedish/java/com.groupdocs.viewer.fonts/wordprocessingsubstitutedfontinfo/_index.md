---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Inkapslar metadata och binär data för ett ersatt teckensnitt som används i ett ordbehandlingsdokument via GroupDocs.Viewer."
type: docs
weight: 18
url: /sv/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Inkapslar metadata och binära data för ett ersatt teckensnitt som används i ett WordProcessing-dokument via GroupDocs.Viewer. Oföränderlig klass.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Konstruktor för att initiera alla fält. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Returnerar familjenamnet för det ersatta teckensnittet (aldrig null). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Returnerar familjenamnet för det ursprungliga teckensnittet (aldrig null). |
|
|  | [getStyle()](#getStyle--) | Returnerar stilen för det ursprungliga teckensnittet. |
|
|  | [getContent()](#getContent--) | Returnerar det binära innehållet för det ersatta teckensnittet (aldrig null). |
|
|  | [getFormat()](#getFormat--) | Returnerar teckensnittets format för det ersatta teckensnittet. |
|
|  | [toString()](#toString--) | Returnerar en sträng som beskriver detta ersatta teckensnitt: "original-namn -> ersatt-namn stil, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Likhet baserad på ursprunglig familj, ersatt familj och stil. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisera detta teckensnitt som en @font-face CSS-regel med en hjälpfunktion. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Konstruktor för att initiera alla fält.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | Det ursprungliga teckensnittets namn (ej funnet på systemet) |
|
|  | substitutedFamilyName | java.lang.String | Det ersatta teckensnittsnamnet (tillgängligt) |
|
|  | stil | com.groupdocs.viewer.fonts.FontStyles | Teckensnittsstil (Regular, Bold, Italic, BoldItalic) |
|
|  | innehåll | byte[] | Binärt innehåll för ersatt teckensnitt (aldrig null) |
|
|  | format | int | Teckensnittformat (TrueType, OpenType, etc.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Returnerar familjenamnet för det ersatta teckensnittet (aldrig null).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Returnerar familjenamnet för det ursprungliga teckensnittet (aldrig null).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Returnerar stilen för det ursprungliga teckensnittet.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Returnerar det binära innehållet för det ersatta teckensnittet (aldrig null).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Returnerar teckensnittets format för det ersatta teckensnittet.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som beskriver detta ersatta teckensnitt: "original-namn -> ersatt-namn stil, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Likhet baserad på original familj, ersatt familj och stil. Krävs för användning i HashSet eller HashMap som C# IEqualityComparer.


**Parameters:**
| Parameter | Typ | Beskrivning |
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


Serialisera detta teckensnitt som en @font-face CSS-regel med en hjälpfunktion.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utdata | java.io.Writer |  |

