---
title: "FontStyles"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les 4 styles possibles de la police utilisés dans le document : Regular, Bold, Italic ou Bold Italic."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Crée une instance FontStyles à partir des indicateurs gras/italique. |
## Champs

| Champ | Description |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [toString(int style)](#toString-int-) | Convertit une valeur de style en une chaîne lisible par l'homme. |
| [getName()](#getName--) | Renvoie le nom lisible de ce style de police. |
| [isBold()](#isBold--) | Renvoie vrai si le bit gras est défini. |
| [isItalic()](#isItalic--) | Renvoie vrai si le bit italique est défini. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Union (opérateur C\# +) |
| [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Différence (opérateur C\# -) |
| [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Analyse un nom de style de police en FontStyles. |
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Crée une instance FontStyles à partir des indicateurs gras/italique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


Convertit une valeur de style en une chaîne lisible par l'homme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | int | la valeur du style de police |

**Returns:**
java.lang.String - une représentation sous forme de chaîne du style de police
### getName() {#getName--}
```
public String getName()
```


Renvoie le nom lisible de ce style de police.

**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Renvoie vrai si le bit gras est défini.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Renvoie vrai si le bit italique est défini.

**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


Union (opérateur C\# +)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| premier | com.groupdocs.viewer.fonts.FontStyles |  |
| deuxième | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Différence (opérateur C\# -)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minuende | com.groupdocs.viewer.fonts.FontStyles |  |
| soustrait | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Analyse un nom de style de police en FontStyles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | java.lang.String |  |
| analysé | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - vrai en cas de succès, faux sinon.
