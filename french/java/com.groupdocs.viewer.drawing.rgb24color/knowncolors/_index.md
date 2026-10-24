---
title: "KnownColors"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: 
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Essaie de trouver une couleur à partir de son nom sous forme de chaîne. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Essaie de trouver le nom d'une couleur à partir de sa valeur RVB. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Essaie de trouver une couleur à partir de son nom sous forme de chaîne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot-clé | java.lang.String | Un nom de couleur. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Le conteneur de résultat pour la couleur trouvée, ou CssLevel1.Black en cas d'échec. |
|

**Returns:**
booléen - True si la couleur a été trouvée avec succès par son nom, false sinon.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Essaie de trouver le nom d'une couleur à partir de sa valeur RVB.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Une instance de couleur. |
|
|  | nom | java.lang.String[] | Le conteneur de résultat pour le nom de couleur trouvé, ou null en cas d'échec. |
|

**Returns:**
booléen - True si le nom a été trouvé avec succès pour la couleur donnée, false sinon.

