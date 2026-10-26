---
title: "Tile"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta la regione di disegno."
type: docs
weight: 33
url: /it/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Rappresenta la regione di disegno.

La classe Tile rappresenta una regione di disegno nel componente GroupDocs.Viewer. Viene utilizzata per definire un'area o regione specifica all'interno di un documento che deve essere renderizzata o elaborata separatamente. Per ulteriori dettagli, vedere la [documentation][].

Esempio di utilizzo:

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Inizializza una nuova istanza della classe  Tile  . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Restituisce la coordinata X del punto più in basso a sinistra del disegno dove inizia la tile. |
| [getStartPointY()](#getStartPointY--) | Restituisce la coordinata Y del punto più in basso a sinistra del disegno dove inizia la tile. |
| [getWidth()](#getWidth--) | Restituisce la larghezza della tile in pixel. |
| [getHeight()](#getHeight--) | Restituisce l'altezza della tile in pixel. |
| [getEndPointX()](#getEndPointX--) | Restituisce la coordinata X del punto più in alto a destra del disegno dove termina la tile. |
| [getEndPointY()](#getEndPointY--) | Restituisce la coordinata Y del punto più in alto a destra del disegno dove termina la tile. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Inizializza una nuova istanza della classe  Tile  .

Questo costruttore crea un nuovo oggetto tile con il punto di partenza, la larghezza e l'altezza specificati. Per ulteriori dettagli, vedere la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPointX | int | La coordinata X del punto più in basso a sinistra del disegno dove inizia la tile. |
| startPointY | int | La coordinata Y del punto più in basso a sinistra del disegno dove inizia la tile. |
| width | int | La larghezza della tile in pixel. |
| height | int | L'altezza della tile in pixel. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Restituisce la coordinata X del punto più in basso a sinistra del disegno dove inizia la tile.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordinata X del punto più in basso a sinistra.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Restituisce la coordinata Y del punto più in basso a sinistra del disegno dove inizia la tile.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la coordinata Y del punto più in basso a sinistra.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza della tile in pixel.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - la larghezza della tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza della tile in pixel.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - l'altezza della tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Restituisce la coordinata X del punto più in alto a destra del disegno dove termina la tile.

**Returns:**
int - la coordinata X del punto più in alto a destra.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Restituisce la coordinata Y del punto più in alto a destra del disegno dove termina la tile.

**Returns:**
int - la coordinata Y del punto più alto a destra.
