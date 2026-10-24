---
title: "PresentationFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Encapsule les métadonnées et les données binaires d’une police utilisée dans un document Presentation chargé dans l’instance Viewer."
type: docs
weight: 15
url: /fr/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Encapsule les métadonnées et les données binaires d’une police utilisée dans un document Presentation, chargé dans l’instance Viewer. Cette police est utilisée dans le contenu du document et peut être intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute GroupDocs.Viewer.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtient le nom de famille de la police (jamais nul ou vide). |
|
|  | [getStyle()](#getStyle--) | Obtient le style de la police : Regular, Bold, Italic ou BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indique si cette police est intégrée dans le document chargé dans l’instance Viewer. |
|
|  | [getFormat()](#getFormat--) | Obtient le format de la police (TrueType, OpenType, etc.). |
|
|  | [getContent()](#getContent--) | Obtient le contenu binaire de la police, ou null si les données de la police sont indisponibles. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialise les informations de cette police en règle CSS @font-face en utilisant le writer spécifié. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtient le nom de famille de la police (jamais nul ou vide).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Obtient le style de la police : Regular, Bold, Italic ou BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indique si cette police est intégrée dans le document chargé dans l’instance Viewer. Remarque : les documents Spreadsheet ne peuvent pas contenir de polices intégrées, donc pour eux cela renvoie toujours false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Obtient le format de la police (TrueType, OpenType, etc.). Si seules les métadonnées sont disponibles, renvoie FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtient le contenu binaire de la police, ou null si les données de la police sont indisponibles.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Sérialise les informations de cette police en règle CSS @font-face en utilisant le writer spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | output | java.io.Writer | writer pour écrire le CSS (ne doit pas être null) |
|

