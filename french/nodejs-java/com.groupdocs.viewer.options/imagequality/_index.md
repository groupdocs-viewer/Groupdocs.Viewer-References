---
title: "ImageQuality"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "La qualité des images dans le HTML de sortie contenu par les documents PDF."
type: docs
weight: 41
url: /fr/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

La qualité des images dans le HTML de sortie contenu par les documents PDF.

L'énumération ImageQuality représente la qualité des images dans le HTML de sortie contenu par les documents PDF du composant GroupDocs.Viewer. Elle fournit différents niveaux de qualité d'image qui peuvent être utilisés pour contrôler le rendu et la compression des images dans le HTML généré.

Exemple d'utilisation :

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Champs

| Champ | Description |
| --- | --- |
| [LOW](#LOW) | La qualité acceptable et les meilleures performances. |
| [MEDIUM](#MEDIUM) | Une meilleure qualité et des performances plus lentes. |
| [HIGH](#HIGH) | La meilleure qualité mais des performances lentes. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


La qualité acceptable et les meilleures performances. Ce paramètre privilégie la vitesse de rendu par rapport à la qualité de l'image.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Une meilleure qualité et des performances plus lentes. Ce paramètre offre un équilibre entre la qualité de l'image et la vitesse de rendu.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


La meilleure qualité mais des performances lentes. Ce paramètre privilégie la qualité de l'image par rapport à la vitesse de rendu.

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
