---
title: "Tile"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar ritområde."
type: docs
weight: 33
url: /sv/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Representerar ritområde.


Klassen Tile representerar ett ritområde i GroupDocs.Viewer-komponenten.
Den används för att definiera ett specifikt område eller region inom ett dokument som måste renderas eller bearbetas separat.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Exempel på användning:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initierar en ny instans av |
Tile
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Hämtar X-koordinaten för den lägsta vänstra punkten på ritningen där tile börjar. |
|
|  | [getStartPointY()](#getStartPointY--) | Hämtar Y‑koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på plattan i pixlar. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på plattan i pixlar. |
|
|  | [getEndPointX()](#getEndPointX--) | Returnerar X‑koordinaten för den högsta högra punkten på ritningen där plattan slutar. |
|
|  | [getEndPointY()](#getEndPointY--) | Returnerar Y‑koordinaten för den högsta högra punkten på ritningen där plattan slutar. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initierar en ny instans av
Tile
klassen.


Denna konstruktor skapar ett nytt plattobjekt med den angivna startpunkten, bredden och höjden.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | startPointX | int | X‑koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
|
|  | startPointY | int | Y‑koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
|
|  | width | int | Bredden på plattan i pixlar. |
|
|  | höjd | int | Höjden på plattan i pixlar. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Hämtar X-koordinaten för den lägsta vänstra punkten på ritningen där tile börjar.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - X‑koordinaten för den lägsta vänstra punkten.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Hämtar Y‑koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - Y‑koordinaten för den lägsta vänstra punkten.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på plattan i pixlar.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - bredden på plattan.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på plattan i pixlar.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - höjden på plattan.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Returnerar X‑koordinaten för den högsta högra punkten på ritningen där plattan slutar.


**Returns:**
int - X‑koordinaten för den högsta högra punkten.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Returnerar Y‑koordinaten för den högsta högra punkten på ritningen där plattan slutar.


**Returns:**
int - Y‑koordinaten för den högsta högra punkten.

