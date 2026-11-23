---
title: "Tile"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt den Zeichenbereich dar."
type: docs
weight: 33
url: /de/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Stellt den Zeichenbereich dar.


Die Tile-Klasse repräsentiert einen Zeichenbereich in der GroupDocs.Viewer-Komponente.
Sie wird verwendet, um einen bestimmten Bereich oder ein bestimmtes Gebiet innerhalb eines Dokuments zu definieren, das separat gerendert oder verarbeitet werden muss.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Beispielverwendung:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initialisiert eine neue Instanz von |
Tile
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Gibt die X‑Koordinate des niedrigsten linken Punktes der Zeichnung zurück, an dem das Tile beginnt. |
|
|  | [getStartPointY()](#getStartPointY--) | Gibt die Y‑Koordinate des niedrigsten linken Punktes der Zeichnung zurück, an dem das Tile beginnt. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite des Tiles in Pixeln zurück. |
|
|  | [getHeight()](#getHeight--) | Gibt die Höhe des Tiles in Pixeln zurück. |
|
|  | [getEndPointX()](#getEndPointX--) | Gibt die X‑Koordinate des höchsten rechten Punktes der Zeichnung zurück, an dem das Tile endet. |
|
|  | [getEndPointY()](#getEndPointY--) | Gibt die Y‑Koordinate des höchsten rechten Punktes der Zeichnung zurück, an dem das Tile endet. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initialisiert eine neue Instanz von
Tile
Klasse.


Dieser Konstruktor erstellt ein neues Tile-Objekt mit dem angegebenen Startpunkt, der Breite und der Höhe.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | startPointX | int | Die X-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem die Kachel beginnt. |
|
|  | startPointY | int | Die Y-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem die Kachel beginnt. |
|
|  | width | int | Die Breite der Kachel in Pixeln. |
|
|  | height | int | Die Höhe der Kachel in Pixeln. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Gibt die X‑Koordinate des niedrigsten linken Punktes der Zeichnung zurück, an dem das Tile beginnt.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - die X-Koordinate des niedrigsten linken Punktes.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Gibt die Y‑Koordinate des niedrigsten linken Punktes der Zeichnung zurück, an dem das Tile beginnt.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - die Y-Koordinate des niedrigsten linken Punktes.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite des Tiles in Pixeln zurück.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - die Breite der Kachel.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe des Tiles in Pixeln zurück.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - die Höhe der Kachel.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Gibt die X‑Koordinate des höchsten rechten Punktes der Zeichnung zurück, an dem das Tile endet.


**Returns:**
int - die X-Koordinate des höchsten rechten Punktes.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Gibt die Y‑Koordinate des höchsten rechten Punktes der Zeichnung zurück, an dem das Tile endet.


**Returns:**
int - die Y-Koordinate des höchsten rechten Punktes.

