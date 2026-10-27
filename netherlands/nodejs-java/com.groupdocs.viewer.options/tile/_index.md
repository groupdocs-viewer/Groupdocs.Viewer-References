---
title: "Tile"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt de tekenregio voor."
type: docs
weight: 33
url: /nl/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Stelt de tekenregio voor.

De Tile-klasse vertegenwoordigt een tekengebied in de GroupDocs.Viewer-component. Het wordt gebruikt om een specifiek gebied of regio binnen een document te definiëren die afzonderlijk moet worden gerenderd of verwerkt. Voor details, zie de [documentation][].

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initialiseert een nieuw exemplaar van de  Tile  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Haalt de X-coördinaat op van het laagste linkerpunt op de tekening waar de tegel begint. |
| [getStartPointY()](#getStartPointY--) | Haalt de Y-coördinaat op van het laagste linkerpunt op de tekening waar de tegel begint. |
| [getWidth()](#getWidth--) | Haalt de breedte van de tegel op in pixels. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de tegel op in pixels. |
| [getEndPointX()](#getEndPointX--) | Retourneert de X-coördinaat van het hoogste rechterpunt op de tekening waar de tegel eindigt. |
| [getEndPointY()](#getEndPointY--) | Retourneert de Y-coördinaat van het hoogste rechterpunt op de tekening waar de tegel eindigt. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initialiseert een nieuw exemplaar van de  Tile  klasse.

Deze constructor maakt een nieuw tegelobject aan met het opgegeven startpunt, de breedte en de hoogte. Voor details, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startPointX | int | De X-coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| startPointY | int | De Y-coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| width | int | De breedte van de tegel in pixels. |
| height | int | De hoogte van de tegel in pixels. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Haalt de X-coördinaat op van het laagste linkerpunt op de tekening waar de tegel begint.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - de X-coördinaat van het laagste linkerpunt.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Haalt de Y-coördinaat op van het laagste linkerpunt op de tekening waar de tegel begint.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - de Y-coördinaat van het laagste linkerpunt.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de tegel op in pixels.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - de breedte van de tegel.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de tegel op in pixels.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - de hoogte van de tegel.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Retourneert de X-coördinaat van het hoogste rechterpunt op de tekening waar de tegel eindigt.

**Returns:**
int - de X-coördinaat van het hoogste rechterpunt.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Retourneert de Y-coördinaat van het hoogste rechterpunt op de tekening waar de tegel eindigt.

**Returns:**
int - de Y-coördinaat van het hoogste rechterpunt.
