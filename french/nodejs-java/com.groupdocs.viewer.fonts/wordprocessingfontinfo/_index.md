---
title: "WordProcessingFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Encapsule les métadonnées et les données binaires d'une police du document WordProcessing chargé dans l'instance du Viewer."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Encapsule les métadonnées et les données binaires d’une police du document WordProcessing, chargé dans l’instance Viewer. Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où GroupDocs.Viewer s’exécute.

Classe immuable. Ses instances sont créées et renvoyées par l’API publique de GroupDocs.Viewer et ne devraient normalement pas être créées par l’utilisateur. Pour plus de détails, consultez la documentation : https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nom de famille de la police, sans style, jamais nul ou vide. |
| [getAltFamilyName()](#getAltFamilyName--) | Nom de famille alternatif de la police. |
| [getStyle()](#getStyle--) | Style de la police \\u2014 peut être Regular, Bold, Italic ou BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Indique si cette police est intégrée dans le document (true) ou une police système (false). |
| [getFormat()](#getFormat--) | Format de cette police. |
| [getContent()](#getContent--) | Contenu de cette police sous forme de tableau d’octets, ou null si indisponible. |
| [getCharset()](#getCharset--) | Jeu de caractères de cette police. |
| [toString()](#toString--) | Renvoie les informations de débogage sur cette police selon le modèle suivant : "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialise les informations de cette police sous forme de règle CSS @font-face et les écrit dans le writer spécifié. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nom de famille de la police, sans style, jamais nul ou vide.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Nom de famille alternatif de la police. Si absent, renvoie une chaîne vide.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Style de la police \\u2014 peut être Regular, Bold, Italic ou BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indique si cette police est intégrée dans le document (true) ou une police système (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format de cette police. S’il n’y a que les métadonnées et que le contenu binaire est absent, peut renvoyer FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenu de cette police sous forme de tableau d’octets, ou null si indisponible.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Jeu de caractères de cette police.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Renvoie les informations de débogage sur cette police selon le modèle suivant : "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Sérialise les informations de cette police sous forme de règle CSS @font-face et les écrit dans le writer spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sortie | java.io.Writer | Writer destiné à recevoir le CSS sérialisé. |

