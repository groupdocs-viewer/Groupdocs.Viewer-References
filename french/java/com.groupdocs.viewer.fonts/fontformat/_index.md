---
title: "FontFormat"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente tous les formats de police qui peuvent être présents dans la classe UsedFontInfo."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Représente tous les formats de police, qui peuvent être présents dans la classe UsedFontInfo.

## Champs

| Champ | Description |
| --- | --- |
|  | [Unknown](#Unknown) | Format de police inconnu ou invalide. |
|
|  | [TrueType](#TrueType) | Format de police TrueType (TTF). |
|
|  | [OpenType](#OpenType) | Format de police OpenType (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | Format de police TrueType Collection (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Format de police Embedded OpenType (EOT). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Convertit une valeur de format en une chaîne lisible par l’homme. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Format de police inconnu ou invalide.


### TrueType {#TrueType}
```
public static final int TrueType
```


Format de police TrueType (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


Format de police OpenType (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Format de police TrueType Collection (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Format de police Embedded OpenType (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Convertit une valeur de format en une chaîne lisible par l’homme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | format | int | la valeur du format de police |
|

**Returns:**
java.lang.String - une représentation sous forme de chaîne du format de police

