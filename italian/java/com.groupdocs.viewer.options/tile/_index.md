---
title: "Tile"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta l'area di disegno."
type: docs
weight: 33
url: /it/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Rappresenta l'area di disegno.


La classe Tile rappresenta una regione di disegno nel componente GroupDocs.Viewer.
Viene utilizzata per definire un'area o una regione specifica all'interno di un documento che deve essere renderizzata o elaborata separatamente.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Esempio di utilizzo:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Inizializza una nuova istanza di |
Tile
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Restituisce la coordinata X del punto più in basso a sinistra del disegno dove inizia la tile. |
|
|  | [getStartPointY()](#getStartPointY--) | Ottiene la coordinata Y del punto più in basso a sinistra nel disegno dove inizia la tessera. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza della tessera in pixel. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza della tessera in pixel. |
|
|  | [getEndPointX()](#getEndPointX--) | Restituisce la coordinata X del punto più in alto a destra nel disegno dove termina la tessera. |
|
|  | [getEndPointY()](#getEndPointY--) | Restituisce la coordinata Y del punto più in alto a destra nel disegno dove termina la tessera. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Inizializza una nuova istanza di
Tile
classe.


Questo costruttore crea un nuovo oggetto tessera con il punto di partenza, la larghezza e l'altezza specificati.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | startPointX | int | La coordinata X del punto più in basso a sinistra nel disegno dove inizia la tessera. |
|
|  | startPointY | int | La coordinata Y del punto più in basso a sinistra nel disegno dove inizia la tessera. |
|
|  | width | int | La larghezza della tessera in pixel. |
|
|  | altezza | int | L'altezza della tessera in pixel. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Restituisce la coordinata X del punto più in basso a sinistra del disegno dove inizia la tile.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la coordinata X del punto più in basso a sinistra.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Ottiene la coordinata Y del punto più in basso a sinistra nel disegno dove inizia la tessera.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la coordinata Y del punto più in basso a sinistra.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza della tessera in pixel.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - la larghezza della tessera.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza della tessera in pixel.
Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - l'altezza della tessera.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Restituisce la coordinata X del punto più in alto a destra nel disegno dove termina la tessera.


**Returns:**
int - la coordinata X del punto più in alto a destra.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Restituisce la coordinata Y del punto più in alto a destra nel disegno dove termina la tessera.


**Returns:**
int - la coordinata Y del punto più in alto a destra.

