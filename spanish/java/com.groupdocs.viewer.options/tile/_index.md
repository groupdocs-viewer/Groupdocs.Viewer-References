---
title: "Tile"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa la región de dibujo."
type: docs
weight: 33
url: /es/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Representa la región de dibujo.


La clase Tile representa una región de dibujo en el componente GroupDocs.Viewer.
Se utiliza para definir un área o región específica dentro de un documento que necesita ser renderizada o procesada por separado.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Ejemplo de uso:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Inicializa una nueva instancia de la |
Tile
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Obtiene la coordenada X del punto más bajo a la izquierda del dibujo donde comienza la loseta. |
|
|  | [getStartPointY()](#getStartPointY--) | Obtiene la coordenada Y del punto más bajo a la izquierda en el dibujo donde comienza la baldosilla. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de la baldosilla en píxeles. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de la baldosilla en píxeles. |
|
|  | [getEndPointX()](#getEndPointX--) | Devuelve la coordenada X del punto más alto a la derecha en el dibujo donde termina la baldosilla. |
|
|  | [getEndPointY()](#getEndPointY--) | Devuelve la coordenada Y del punto más alto a la derecha en el dibujo donde termina la baldosilla. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Inicializa una nueva instancia de la
Tile
clase.


Este constructor crea un nuevo objeto baldosilla con el punto de inicio, ancho y altura especificados.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | startPointX | int | La coordenada X del punto más bajo a la izquierda en el dibujo donde comienza la baldosilla. |
|
|  | startPointY | int | La coordenada Y del punto más bajo a la izquierda en el dibujo donde comienza la baldosilla. |
|
|  | width | int | El ancho de la baldosilla en píxeles. |
|
|  | altura | int | La altura de la baldosilla en píxeles. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Obtiene la coordenada X del punto más bajo a la izquierda del dibujo donde comienza la loseta.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la coordenada X del punto más bajo a la izquierda.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Obtiene la coordenada Y del punto más bajo a la izquierda en el dibujo donde comienza la baldosilla.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la coordenada Y del punto más bajo a la izquierda.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de la baldosilla en píxeles.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - el ancho de la baldosilla.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de la baldosilla en píxeles.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la altura de la baldosilla.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Devuelve la coordenada X del punto más alto a la derecha en el dibujo donde termina la baldosilla.


**Returns:**
int - la coordenada X del punto más alto a la derecha.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Devuelve la coordenada Y del punto más alto a la derecha en el dibujo donde termina la baldosilla.


**Returns:**
int - la coordenada Y del punto más alto a la derecha.

