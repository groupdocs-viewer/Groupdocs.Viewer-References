---
title: "Tile"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa la región de dibujo."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Representa la región de dibujo.

La clase Tile representa una región de dibujo en el componente GroupDocs.Viewer. Se utiliza para definir un área o región específica dentro de un documento que necesita ser renderizada o procesada por separado. Para más detalles, consulte la [documentación][].

Ejemplo de uso:

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Inicializa una nueva instancia de la clase  Tile  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Obtiene la coordenada X del punto inferior izquierdo en el dibujo donde comienza la tile. |
| [getStartPointY()](#getStartPointY--) | Obtiene la coordenada Y del punto inferior izquierdo en el dibujo donde comienza la tile. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la tile en píxeles. |
| [getHeight()](#getHeight--) | Obtiene la altura de la tile en píxeles. |
| [getEndPointX()](#getEndPointX--) | Devuelve la coordenada X del punto superior derecho en el dibujo donde termina la tile. |
| [getEndPointY()](#getEndPointY--) | Devuelve la coordenada Y del punto superior derecho en el dibujo donde termina la tile. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Inicializa una nueva instancia de la clase  Tile  .

Este constructor crea un nuevo objeto tile con el punto de inicio especificado, ancho y altura. Para más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startPointX | int | La coordenada X del punto inferior izquierdo en el dibujo donde comienza la tile. |
| startPointY | int | La coordenada Y del punto inferior izquierdo en el dibujo donde comienza la tile. |
| width | int | El ancho de la tile en píxeles. |
| height | int | La altura de la tile en píxeles. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Obtiene la coordenada X del punto inferior izquierdo en el dibujo donde comienza la tile.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordenada X del punto inferior izquierdo.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Obtiene la coordenada Y del punto inferior izquierdo en el dibujo donde comienza la tile.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordenada Y del punto inferior izquierdo.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de la tile en píxeles.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - el ancho de la tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de la tile en píxeles.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la altura de la tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Devuelve la coordenada X del punto superior derecho en el dibujo donde termina la tile.

**Returns:**
int - la coordenada X del punto superior derecho.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Devuelve la coordenada Y del punto superior derecho en el dibujo donde termina la tile.

**Returns:**
int - la coordenada Y del punto más alto a la derecha.
