---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Incapsula metadati e dati binari di un font sostituito usato in un documento WordProcessing tramite GroupDocs.Viewer."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Incapsula i metadati e i dati binari di un font sostituito utilizzato in un documento WordProcessing tramite GroupDocs.Viewer. Classe immutabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Costruttore per inizializzare tutti i campi. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Restituisce il nome della famiglia del font sostituito (mai null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Restituisce il nome della famiglia del font originale (mai null). |
| [getStyle()](#getStyle--) | Restituisce lo stile del font originale. |
| [getContent()](#getContent--) | Restituisce il contenuto binario del font sostituito (mai null). |
| [getFormat()](#getFormat--) | Restituisce il formato del font sostituito. |
| [toString()](#toString--) | Restituisce una stringa che descrive questo font sostituito: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Uguaglianza basata sulla famiglia originale, sulla famiglia sostituita e sullo stile. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza questo font come regola CSS @font-face usando un metodo di utilità. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Costruttore per inizializzare tutti i campi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFamilyName | java.lang.String | Il nome del font originale (non trovato nel sistema) |
| substitutedFamilyName | java.lang.String | Il nome del font sostituito (disponibile) |
| stile | com.groupdocs.viewer.fonts.FontStyles | Stile del font (Regular, Bold, Italic, BoldItalic) |
| content | byte[] | Contenuto binario del font sostituito (mai null) |
| format | int | Formato del font (TrueType, OpenType, ecc.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Restituisce il nome della famiglia del font sostituito (mai null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Restituisce il nome della famiglia del font originale (mai null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Restituisce lo stile del font originale.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Restituisce il contenuto binario del font sostituito (mai null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Restituisce il formato del font sostituito.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che descrive questo font sostituito: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Uguaglianza basata sulla famiglia originale, sulla famiglia sostituita e sullo stile. Necessario per l'uso in HashSet o HashMap come C\\# IEqualityComparer.

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Serializza questo font come regola CSS @font-face usando un metodo di utilità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | java.io.Writer |  |

