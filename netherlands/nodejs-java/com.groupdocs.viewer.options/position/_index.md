---
title: "Position"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Definieert de positie van het watermerk."
type: docs
weight: 43
url: /nl/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Definieert de positie van het watermerk.

De Position-enum vertegenwoordigt verschillende posities voor een watermark in de GroupDocs.Viewer-component. Het biedt een set vooraf gedefinieerde posities die kunnen worden gebruikt om de plaatsing van een watermark op een document of afbeelding tijdens het renderproces te specificeren.

Voorbeeldgebruik:

```

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
 
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | De diagonale positie. |
| [TOP_LEFT](#TOP-LEFT) | De positie linksboven. |
| [TOP_CENTER](#TOP-CENTER) | De positie bovenmidden. |
| [TOP_RIGHT](#TOP-RIGHT) | De positie rechtsboven. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | De positie linksonder. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | De positie middenonder. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | De positie rechtsonder. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


De diagonale positie. Deze positie vertegenwoordigt een diagonale uitlijning of plaatsing.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


De positie linksboven. Deze positie vertegenwoordigt de uitlijning of plaatsing in de linkerbovenhoek.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


De positie bovenmidden. Deze positie vertegenwoordigt de uitlijning of plaatsing in het bovenmidden.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


De positie rechtsboven. Deze positie vertegenwoordigt de uitlijning of plaatsing in de rechterbovenhoek.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


De positie linksonder. Deze positie vertegenwoordigt de uitlijning of plaatsing in de linkeronderhoek.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


De positie middenonder. Deze positie vertegenwoordigt de uitlijning of plaatsing in het middenonder.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


De positie rechtsonder. Deze positie vertegenwoordigt de uitlijning of plaatsing in de rechteronderhoek.

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
| naam | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
