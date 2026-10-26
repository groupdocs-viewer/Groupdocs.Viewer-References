---
title: "Tile"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente la région de dessin."
type: docs
weight: 33
url: /fr/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Représente la région de dessin.

La classe Tile représente une région de dessin dans le composant GroupDocs.Viewer. Elle est utilisée pour définir une zone ou région spécifique au sein d'un document qui doit être rendue ou traitée séparément. Pour plus de détails, voir la [documentation][].

Exemple d'utilisation :

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initialise une nouvelle instance de la classe  Tile . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Obtient la coordonnée X du point le plus bas à gauche du dessin où le tile commence. |
| [getStartPointY()](#getStartPointY--) | Obtient la coordonnée Y du point le plus bas à gauche du dessin où le tile commence. |
| [getWidth()](#getWidth--) | Obtient la largeur du tile en pixels. |
| [getHeight()](#getHeight--) | Obtient la hauteur du tile en pixels. |
| [getEndPointX()](#getEndPointX--) | Renvoie la coordonnée X du point le plus haut à droite du dessin où le tile se termine. |
| [getEndPointY()](#getEndPointY--) | Renvoie la coordonnée Y du point le plus haut à droite du dessin où le tile se termine. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initialise une nouvelle instance de la classe  Tile .

Ce constructeur crée un nouvel objet tile avec le point de départ, la largeur et la hauteur spécifiés. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startPointX | int | La coordonnée X du point le plus bas à gauche du dessin où le tile commence. |
| startPointY | int | La coordonnée Y du point le plus bas à gauche du dessin où le tile commence. |
| width | int | La largeur du tile en pixels. |
| height | int | La hauteur du tile en pixels. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Obtient la coordonnée X du point le plus bas à gauche du dessin où le tile commence.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordonnée X du point le plus bas à gauche.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Obtient la coordonnée Y du point le plus bas à gauche du dessin où le tile commence.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordonnée Y du point le plus bas à gauche.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur du tile en pixels.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la largeur du tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur du tile en pixels.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la hauteur du tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Renvoie la coordonnée X du point le plus haut à droite du dessin où le tile se termine.

**Returns:**
int - la coordonnée X du point le plus haut à droite.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Renvoie la coordonnée Y du point le plus haut à droite du dessin où le tile se termine.

**Returns:**
int - la coordonnée Y du point le plus à droite en haut.
