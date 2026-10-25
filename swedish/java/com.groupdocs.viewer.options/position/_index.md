---
title: "Position"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Definierar vattenstämpelns position."
type: docs
weight: 43
url: /sv/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Definierar vattenstämpelns position.


Enumen Position representerar olika positioner för ett vattenstämpel i GroupDocs.Viewer-komponenten.
Den tillhandahåller en uppsättning fördefinierade positioner som kan användas för att ange placeringen av en vattenstämpel
på ett dokument eller en bild under renderingsprocessen.


Exempel på användning:

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


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | Den diagonala positionen. |
|
|  | [TOP_LEFT](#TOP-LEFT) | Den övre vänstra positionen. |
|
|  | [TOP_CENTER](#TOP-CENTER) | Den övre centrala positionen. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | Den övre högra positionen. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | Den nedre vänstra positionen. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | Den nedre centrala positionen. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Den nedre högra positionen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Den diagonala positionen.
Denna position representerar en diagonal justering eller placering.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Den övre vänstra positionen.
Denna position representerar den övre vänstra hörnjusteringen eller placeringen.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Den övre centrala positionen.
Denna position representerar den övre centrala justeringen eller placeringen.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Den övre högra positionen.
Denna position representerar den övre högra hörnjusteringen eller placeringen.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Den nedre vänstra positionen.
Denna position representerar den nedre vänstra hörnjusteringen eller placeringen.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Den nedre centrala positionen.
Denna position representerar den nedre centrala justeringen eller placeringen.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Den nedre högra positionen.
Denna position representerar den nedre högra hörnjusteringen eller placeringen.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
