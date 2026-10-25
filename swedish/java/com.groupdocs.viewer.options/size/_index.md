---
title: "Size"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Innehåller vattenstämpelns storlek."
type: docs
weight: 30
url: /sv/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Innehåller vattenstämpelns storlek.


Klassen Size representerar storleken på ett vattenmärke i GroupDocs.Viewer-komponenten.
Den tillhandahåller alternativ för att ange vattenmärkets dimensioner, såsom bredd och höjd.


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


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Initierar en ny instans av |
Size
klassen.
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Representerar den maximala storleken på vattenstämpeltext som får plats på sidan. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Representerar hälften av den maximala storleken på vattenstämpeltext som får plats på sidan. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Representerar en tredjedel av den maximala storleken på vattenstämpeltext som får plats på sidan. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Returnerar vattenstämpeltextens storlek i procent i förhållande till sidans bredd. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initierar en ny instans av
Size
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | relativeSize | byte | Storleken i procent i förhållande till sidans storlek. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Representerar den maximala storleken på vattenstämpeltext som får plats på sidan.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Representerar hälften av den maximala storleken på vattenstämpeltext som får plats på sidan.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Representerar en tredjedel av den maximala storleken på vattenstämpeltext som får plats på sidan.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Returnerar vattenstämpeltextens storlek i procent i förhållande till sidans bredd.


**Returns:**
byte - vattenstämpeltextens storlek i procent.

