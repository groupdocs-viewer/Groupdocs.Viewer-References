---
title: "ImageQuality"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "La qualité des images dans le HTML de sortie contenu par les documents PDF."
type: docs
weight: 41
url: /fr/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

La qualité des images dans le HTML de sortie contenu par les documents PDF.


L'énumération ImageQuality représente la qualité des images dans le HTML de sortie contenu par les documents PDF
dans le composant GroupDocs.Viewer. Il fournit différents niveaux de qualité d'image qui peuvent être utilisés
pour contrôler le rendu et la compression des images dans la sortie HTML générée.


Exemple d'utilisation :

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [LOW](#LOW) | Qualité acceptable et meilleures performances. |
|
|  | [MEDIUM](#MEDIUM) | Meilleure qualité et performances plus lentes. |
|
|  | [HIGH](#HIGH) | La meilleure qualité mais performances lentes. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Qualité acceptable et meilleures performances.
Ce paramètre privilégie la vitesse de rendu plutôt que la qualité d'image.


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Meilleure qualité et performances plus lentes.
Ce paramètre offre un équilibre entre la qualité d'image et la vitesse de rendu.


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


La meilleure qualité mais performances lentes.
Ce paramètre privilégie la qualité d'image plutôt que la vitesse de rendu.


### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
