---
title: "WordProcessingFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Encapsule les métadonnées et les données binaires d'une police du document WordProcessing chargé dans l'instance Viewer."
type: docs
weight: 17
url: /fr/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Encapsule les métadonnées et les données binaires d'une police du document WordProcessing, chargé dans l'instance Viewer. Cette police est utilisée dans le contenu du document et est intégrée au document lui‑même ou installée dans le système d'exploitation où s'exécute GroupDocs.Viewer.

Classe immuable. Ses instances sont créées et renvoyées par le GroupDocs.Viewer
API publique et ne devrait normalement pas être créée par l'utilisateur.
Pour plus de détails, consultez la documentation:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Nom de famille de la police, sans style, jamais nul ou vide. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Nom de famille alternatif de la police. |
|
|  | [getStyle()](#getStyle--) | Style de la police — peut être Regular, Bold, Italic ou BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indique si cette police est intégrée dans le document (true) ou une police système (false). |
|
|  | [getFormat()](#getFormat--) | Format de cette police. |
|
|  | [getContent()](#getContent--) | Contenu de cette police sous forme de tableau d’octets, ou null si indisponible. |
|
|  | [getCharset()](#getCharset--) | Jeu de caractères de cette police. |
|
|  | [toString()](#toString--) | Renvoie les informations de débogage sur cette police selon le modèle suivant : "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialise les informations de cette police en tant que règle CSS @font-face et les écrit dans le writer spécifié. |
|
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


Style de la police — peut être Regular, Bold, Italic ou BoldItalic.


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


Format de cette police. S’il n’y a que des métadonnées et que le contenu binaire est manquant, peut renvoyer FontFormat.UNKNOWN.


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


Sérialise les informations de cette police en tant que règle CSS @font-face et les écrit dans le writer spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | output | java.io.Writer | Writer qui recevra le CSS sérialisé. |
|

