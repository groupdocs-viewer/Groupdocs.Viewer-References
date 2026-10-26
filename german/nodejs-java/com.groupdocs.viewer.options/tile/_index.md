---
title: "Tile"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt den Zeichenbereich dar."
type: docs
weight: 33
url: /de/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Stellt den Zeichenbereich dar.

Die Tile‑Klasse stellt einen Zeichenbereich in der GroupDocs.Viewer‑Komponente dar. Sie wird verwendet, um einen bestimmten Bereich oder ein bestimmtes Gebiet innerhalb eines Dokuments zu definieren, das separat gerendert oder verarbeitet werden muss. Weitere Details siehe die [documentation][].

Beispielhafte Verwendung:

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Initialisiert eine neue Instanz der Tile‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Gibt die X‑Koordinate des niedrigsten linken Punktes in der Zeichnung zurück, an dem das Tile beginnt. |
| [getStartPointY()](#getStartPointY--) | Gibt die Y‑Koordinate des niedrigsten linken Punktes in der Zeichnung zurück, an dem das Tile beginnt. |
| [getWidth()](#getWidth--) | Gibt die Breite des Tiles in Pixeln zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe des Tiles in Pixeln zurück. |
| [getEndPointX()](#getEndPointX--) | Gibt die X‑Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet. |
| [getEndPointY()](#getEndPointY--) | Gibt die Y‑Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Initialisiert eine neue Instanz der Tile‑Klasse.

Dieser Konstruktor erstellt ein neues Tile‑Objekt mit dem angegebenen Startpunkt, der Breite und der Höhe. Weitere Details siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startPointX | int | Die X‑Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| startPointY | int | Die Y‑Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| width | int | Die Breite des Tiles in Pixeln. |
| height | int | Die Höhe des Tiles in Pixeln. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Gibt die X‑Koordinate des niedrigsten linken Punktes in der Zeichnung zurück, an dem das Tile beginnt.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - die X‑Koordinate des niedrigsten linken Punktes.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Gibt die Y‑Koordinate des niedrigsten linken Punktes in der Zeichnung zurück, an dem das Tile beginnt.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - die Y‑Koordinate des niedrigsten linken Punktes.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite des Tiles in Pixeln zurück.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - die Breite des Tiles.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe des Tiles in Pixeln zurück.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - die Höhe des Tiles.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Gibt die X‑Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet.

**Returns:**
int - die X‑Koordinate des höchsten rechten Punktes.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Gibt die Y‑Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet.

**Returns:**
int - die Y‑Koordinate des höchsten rechten Punktes.
