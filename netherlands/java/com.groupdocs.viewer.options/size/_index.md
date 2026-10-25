---
title: "Size"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Bevat de watermerkgrootte."
type: docs
weight: 30
url: /nl/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Bevat de watermerkgrootte.


De Size-klasse vertegenwoordigt de grootte van een watermerk in de GroupDocs.Viewer-component.
Het biedt opties om de afmetingen van het watermerk op te geven, zoals breedte en hoogte.


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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Initialiseert een nieuw exemplaar van de |
Size
klasse.
|
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Stelt de maximale grootte van watermerktekst voor die op de pagina past. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Stelt de helft van de maximale grootte van watermerktekst voor die op de pagina past. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Stelt een derde van de maximale grootte van watermerktekst voor die op de pagina past. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Geeft de grootte van de watermerktekst in percentages terug in verhouding tot de paginabreedte. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initialiseert een nieuw exemplaar van de
Size
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | relativeSize | byte | De grootte in percentages in verhouding tot de paginagrootte. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Stelt de maximale grootte van watermerktekst voor die op de pagina past.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Stelt de helft van de maximale grootte van watermerktekst voor die op de pagina past.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Stelt een derde van de maximale grootte van watermerktekst voor die op de pagina past.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Geeft de grootte van de watermerktekst in percentages terug in verhouding tot de paginabreedte.


**Returns:**
byte - de grootte van de watermerktekst in percentages.

