---
title: "Position"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Définit la position du filigrane."
type: docs
weight: 43
url: /fr/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Définit la position du filigrane.

L'énumération Position représente différentes positions pour un filigrane dans le composant GroupDocs.Viewer. Elle fournit un ensemble de positions prédéfinies qui peuvent être utilisées pour spécifier le placement d'un filigrane sur un document ou une image lors du processus de rendu.

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
## Champs

| Champ | Description |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | La position diagonale. |
| [TOP_LEFT](#TOP-LEFT) | La position en haut à gauche. |
| [TOP_CENTER](#TOP-CENTER) | La position en haut au centre. |
| [TOP_RIGHT](#TOP-RIGHT) | La position en haut à droite. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | La position en bas à gauche. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | La position en bas au centre. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | La position en bas à droite. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


La position diagonale. Cette position représente un alignement ou un placement diagonal.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


La position en haut à gauche. Cette position représente un alignement ou un placement dans le coin supérieur gauche.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


La position en haut au centre. Cette position représente un alignement ou un placement au centre supérieur.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


La position en haut à droite. Cette position représente un alignement ou un placement dans le coin supérieur droit.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


La position en bas à gauche. Cette position représente un alignement ou un placement dans le coin inférieur gauche.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


La position en bas au centre. Cette position représente un alignement ou un placement au centre inférieur.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


La position en bas à droite. Cette position représente un alignement ou un placement dans le coin inférieur droit.

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
