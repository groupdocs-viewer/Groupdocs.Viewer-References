---
title: "Size"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Innehåller vattenstämpelns storlek."
type: docs
weight: 30
url: /sv/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Innehåller vattenstämpelns storlek.

Size‑klassen representerar storleken på ett vattenmärke i GroupDocs.Viewer‑komponenten. Den tillhandahåller alternativ för att specificera vattenmärkets dimensioner, såsom bredd och höjd.

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Initierar en ny instans av Size‑klassen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Representerar den maximala storleken på vattenmärkestext som får plats på sidan. |
| [HALF_SIZE](#HALF-SIZE) | Representerar hälften av den maximala storleken på vattenmärkestext som får plats på sidan. |
| [ONE_THIRD](#ONE-THIRD) | Representerar en tredjedel av den maximala storleken på vattenmärkestext som får plats på sidan. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Returnerar vattenmärkestextens storlek i procent i förhållande till sidans bredd. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initierar en ny instans av Size‑klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| relativeSize | byte | Storleken i procent i förhållande till sidans storlek. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Representerar den maximala storleken på vattenmärkestext som får plats på sidan.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Representerar hälften av den maximala storleken på vattenmärkestext som får plats på sidan.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Representerar en tredjedel av den maximala storleken på vattenmärkestext som får plats på sidan.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Returnerar vattenmärkestextens storlek i procent i förhållande till sidans bredd.

**Returns:**
byte - vattenmärkestextens storlek i procent.
