---
title: "Rotation"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Contient la rotation de la page en degrés dans le sens des aiguilles d'une montre."
type: docs
weight: 45
url: /fr/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Contient la rotation de la page en degrés (dans le sens des aiguilles d'une montre).


L'énumération Rotation représente différents angles de rotation pour une page dans le composant GroupDocs.Viewer.
Elle fournit un ensemble d'options de rotation prédéfinies qui peuvent être utilisées pour spécifier l'angle de rotation
pour le rendu d'une page dans divers scénarios de visualisation ou de conversion de documents.


Exemple d'utilisation :

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | La rotation de page de 90 degrés. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | La rotation de page de 180 degrés. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | La rotation de page de 270 degrés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


La rotation de page de 90 degrés.
Cette rotation représente une rotation de la page de 90 degrés dans le sens des aiguilles d'une montre.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


La rotation de page de 180 degrés.
Cette rotation représente une rotation de la page de 180 degrés dans le sens des aiguilles d'une montre.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


La rotation de page de 270 degrés.
Cette rotation représente une rotation de la page de 270 degrés dans le sens des aiguilles d'une montre.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
