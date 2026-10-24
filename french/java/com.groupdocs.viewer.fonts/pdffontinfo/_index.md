---
title: "PdfFontInfo"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Encapsule les méta-informations et les données binaires d'une police provenant d'un document PDF chargé dans l'instance du Viewer."
type: docs
weight: 14
url: /fr/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Encapsule les méta‑informations et les données binaires d’une police provenant d’un document PDF, chargé dans l’instance Viewer.


Cette police est utilisée dans le contenu du document et est soit :

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Constructeur interne utilisé par l'extraction de polices PDF. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtient le nom de la famille de la police. |
|
|  | [getStyle()](#getStyle--) | Obtient le style de cette police. |
|
|  | [isEmbedded()](#isEmbedded--) | Renvoie si la police est intégrée dans le document PDF. |
|
|  | [isInstalled()](#isInstalled--) | Renvoie si la police est installée dans le système d'exploitation. |
|
|  | [getFormat()](#getFormat--) | Renvoie le format de fichier de la police. |
|
|  | [getContent()](#getContent--) | Renvoie le contenu binaire de la police. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Sérialise cette police en tant que règle CSS @font-face. |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Constructeur interne utilisé par l'extraction de polices PDF.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | familyName | java.lang.String | nom de famille de police |
|
|  | style | com.groupdocs.viewer.fonts.FontStyles | style (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | true si la police est intégrée dans le PDF |
|
|  | isInstalled | boolean | true si la police est installée dans le système d'exploitation |
|
|  | content | byte[] | données binaires de police (nullable) |
|
|  | format | int | format de fichier de police |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtient le nom de la famille de la police.


**Returns:**
java.lang.String - chaîne du nom de famille (jamais null ou vide)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Obtient le style de cette police.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - le style de police

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Renvoie si la police est intégrée dans le document PDF.


**Returns:**
boolean - true si intégrée

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Renvoie si la police est installée dans le système d'exploitation.


**Returns:**
boolean - true si installée

### getFormat() {#getFormat--}
```
public int getFormat()
```


Renvoie le format de fichier de la police.


**Returns:**
int - l'énumération du format de police

### getContent() {#getContent--}
```
public byte[] getContent()
```


Renvoie le contenu binaire de la police.


**Returns:**
byte[] - tableau d'octets ou null si non disponible

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Sérialise cette police en tant que règle CSS @font-face.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | output | java.io.Writer | writer vers lequel le CSS sera écrit |
|

