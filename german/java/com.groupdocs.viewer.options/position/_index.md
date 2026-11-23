---
title: "Position"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Definiert die Position des Wasserzeichens."
type: docs
weight: 43
url: /de/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Definiert die Position des Wasserzeichens.


Das Position‑Enum repräsentiert verschiedene Positionen für ein Wasserzeichen in der GroupDocs.Viewer‑Komponente.
Es bietet eine Reihe vordefinierter Positionen, die verwendet werden können, um die Platzierung eines Wasserzeichens festzulegen.
auf ein Dokument oder Bild während des Renderings.


Beispielverwendung:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | Die diagonale Position. |
|
|  | [TOP_LEFT](#TOP-LEFT) | Die obere linke Position. |
|
|  | [TOP_CENTER](#TOP-CENTER) | Die obere mittlere Position. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | Die obere rechte Position. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | Die untere linke Position. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | Die untere mittlere Position. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Die untere rechte Position. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Die diagonale Position.
Diese Position stellt eine diagonale Ausrichtung oder Platzierung dar.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Die obere linke Position.
Diese Position stellt die Ausrichtung oder Platzierung in der oberen linken Ecke dar.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Die obere mittlere Position.
Diese Position stellt die Ausrichtung oder Platzierung in der oberen Mitte dar.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Die obere rechte Position.
Diese Position stellt die Ausrichtung oder Platzierung in der oberen rechten Ecke dar.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Die untere linke Position.
Diese Position stellt die Ausrichtung oder Platzierung in der unteren linken Ecke dar.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Die untere mittlere Position.
Diese Position stellt die Ausrichtung oder Platzierung in der unteren Mitte dar.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Die untere rechte Position.
Diese Position stellt die Ausrichtung oder Platzierung in der unteren rechten Ecke dar.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
