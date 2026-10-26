---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Encapsule les métadonnées et les données binaires d'une police substituée utilisée dans un document WordProcessing via GroupDocs.Viewer."
type: docs
weight: 18
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Encapsule les métadonnées et les données binaires d'une police substituée utilisée dans un document WordProcessing via GroupDocs.Viewer. Classe immuable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Constructeur pour initialiser tous les champs. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Renvoie le nom de famille de la police substituée (jamais null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Renvoie le nom de famille de la police originale (jamais null). |
| [getStyle()](#getStyle--) | Renvoie le style de la police originale. |
| [getContent()](#getContent--) | Renvoie le contenu binaire de la police substituée (jamais null). |
| [getFormat()](#getFormat--) | Renvoie le format de police de la police substituée. |
| [toString()](#toString--) | Renvoie une chaîne décrivant cette police substituée : "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Égalité basée sur la famille originale, la famille substituée et le style. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialiser cette police en règle CSS @font-face à l'aide d'une méthode utilitaire. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Constructeur pour initialiser tous les champs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| originalFamilyName | java.lang.String | Le nom de la police originale (non trouvé sur le système) |
| substitutedFamilyName | java.lang.String | Le nom de la police substituée (disponible) |
| style | com.groupdocs.viewer.fonts.FontStyles | Style de police (Regular, Bold, Italic, BoldItalic) |
| contenu | byte[] | Contenu binaire de la police substituée (jamais null) |
| format | int | Format de police (TrueType, OpenType, etc.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Renvoie le nom de famille de la police substituée (jamais null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Renvoie le nom de famille de la police originale (jamais null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Renvoie le style de la police originale.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Renvoie le contenu binaire de la police substituée (jamais null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Renvoie le format de police de la police substituée.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne décrivant cette police substituée : "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Égalité basée sur la famille originale, la famille substituée et le style. Nécessaire pour une utilisation dans HashSet ou HashMap comme C\# IEqualityComparer.

**Parameters:**
| Paramètre | Type | Description |
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


Sérialiser cette police en règle CSS @font-face à l'aide d'une méthode utilitaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sortie | java.io.Writer |  |

