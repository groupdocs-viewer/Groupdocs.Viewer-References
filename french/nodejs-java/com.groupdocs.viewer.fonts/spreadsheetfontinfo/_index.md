---
title: "SpreadsheetFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Encapsule les métadonnées et les données binaires d’une police du document Spreadsheet chargé dans l’instance Viewer."
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Encapsule les métadonnées et les données binaires d’une police du document Spreadsheet, chargé dans l’instance Viewer. Les documents Spreadsheet ne peuvent pas contenir de polices intégrées, ainsi cette police particulière, si elle est renvoyée par la méthode Viewer.getAllFonts(), est installée dans le système d’exploitation où GroupDocs.Viewer s’exécute.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nom de famille de la police, sans style, jamais nul ou vide. |
| [getStyle()](#getStyle--) | Style de cette police — peut être Regular, Bold, Italic ou BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Indique si la police est barrée d’une seule ligne. |
| [isUnderline()](#isUnderline--) | Indique si la police est soulignée. |
| [getColor()](#getColor--) | Couleur de cette police. |
| [getCharset()](#getCharset--) | Jeu de caractères de cette police. |
| [getContent()](#getContent--) | Contenu de cette police sous forme de tableau d’octets. |
| [getFormat()](#getFormat--) | Format de cette police. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialise les informations de cette police en tant que règle @font-face et les écrit dans l’écrivain spécifié. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nom de famille de la police, sans style, jamais nul ou vide.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Style de cette police — peut être Regular, Bold, Italic ou BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indique si la police est barrée d’une seule ligne.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indique si la police est soulignée.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Couleur de cette police.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Jeu de caractères de cette police.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenu de cette police sous forme de tableau d’octets. Peut être nul si seules les métadonnées sont disponibles.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format de cette police.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Sérialise les informations de cette police en tant que règle @font-face et les écrit dans l’écrivain spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sortie | java.io.Writer | Dispositif dans lequel écrire les données texte sérialisées. |

