---
title: Tile
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents drawing region.
type: docs
weight: 33
url: /nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Represents drawing region.

The Tile class represents a drawing region in the GroupDocs.Viewer component. It is used to define a specific area or region within a document that needs to be rendered or processed separately. For details, see the [documentation][].

Example usage:

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

| Constructor | Description |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initializes a new instance of the  Tile  class. |
## Methods

| Method | Description |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Gets the X coordinate of the lowest left point on the drawing where the tile begins. |
| [getStartPointY()](#getStartPointY--) | Gets the Y coordinate of the lowest left point on the drawing where the tile begins. |
| [getWidth()](#getWidth--) | Gets the width of the tile in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the tile in pixels. |
| [getEndPointX()](#getEndPointX--) | Returns the X coordinate of the highest right point on the drawing where the tile ends. |
| [getEndPointY()](#getEndPointY--) | Returns the Y coordinate of the highest right point on the drawing where the tile ends. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initializes a new instance of the  Tile  class.

This constructor creates a new tile object with the specified starting point, width, and height. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPointX | int | The X coordinate of the lowest left point on the drawing where the tile begins. |
| startPointY | int | The Y coordinate of the lowest left point on the drawing where the tile begins. |
| width | int | The width of the tile in pixels. |
| height | int | The height of the tile in pixels. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Gets the X coordinate of the lowest left point on the drawing where the tile begins.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - the X coordinate of the lowest left point.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Gets the Y coordinate of the lowest left point on the drawing where the tile begins.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - the Y coordinate of the lowest left point.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the tile in pixels.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - the width of the tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the tile in pixels.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - the height of the tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Returns the X coordinate of the highest right point on the drawing where the tile ends.

**Returns:**
int - the X coordinate of the highest right point.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Returns the Y coordinate of the highest right point on the drawing where the tile ends.

**Returns:**
int - the Y coordinate of the highest right point.
