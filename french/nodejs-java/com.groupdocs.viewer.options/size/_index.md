---
title: "Size"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Contient la taille du filigrane."
type: docs
weight: 30
url: /fr/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Contient la taille du filigrane.

La classe Size représente la taille d'un filigrane dans le composant GroupDocs.Viewer. Elle offre des options pour spécifier les dimensions du filigrane, telles que la largeur et la hauteur.

Exemple d'utilisation :

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Initialise une nouvelle instance de la classe Size. |
## Champs

| Champ | Description |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Représente la taille maximale du texte du filigrane qui tient sur la page. |
| [HALF_SIZE](#HALF-SIZE) | Représente la moitié de la taille maximale du texte du filigrane qui tient sur la page. |
| [ONE_THIRD](#ONE-THIRD) | Représente un tiers de la taille maximale du texte du filigrane qui tient sur la page. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Renvoie la taille du texte du filigrane en pourcentage par rapport à la largeur de la page. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initialise une nouvelle instance de la classe Size.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| relativeSize | byte | La taille en pourcentage par rapport à la taille de la page. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Représente la taille maximale du texte du filigrane qui tient sur la page.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Représente la moitié de la taille maximale du texte du filigrane qui tient sur la page.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Représente un tiers de la taille maximale du texte du filigrane qui tient sur la page.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Renvoie la taille du texte du filigrane en pourcentage par rapport à la largeur de la page.

**Returns:**
byte - la taille du texte du filigrane en pourcentage.
