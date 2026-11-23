---
title: "Position"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Definieert de positie van het watermerk."
type: docs
weight: 43
url: /nl/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Definieert de positie van het watermerk.


De Position enum vertegenwoordigt verschillende posities voor een watermerk in de GroupDocs.Viewer component.
Het biedt een reeks vooraf gedefinieerde posities die kunnen worden gebruikt om de plaatsing van een watermerk te specificeren
op een document of afbeelding tijdens het renderproces.


Voorbeeldgebruik:

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


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | De diagonale positie. |
|
|  | [TOP_LEFT](#TOP-LEFT) | De linkerboven positie. |
|
|  | [TOP_CENTER](#TOP-CENTER) | De bovenmidden positie. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | De rechterboven positie. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | De linksonder positie. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | De ondermidden positie. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | De rechteronder positie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


De diagonale positie.
Deze positie vertegenwoordigt een diagonale uitlijning of plaatsing.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


De linkerboven positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van de linkerbovenhoek.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


De bovenmidden positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van het bovenmidden.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


De rechterboven positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van de rechterbovenhoek.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


De linksonder positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van de linksonderhoek.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


De ondermidden positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van het ondermidden.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


De rechteronder positie.
Deze positie vertegenwoordigt de uitlijning of plaatsing van de rechteronderhoek.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
