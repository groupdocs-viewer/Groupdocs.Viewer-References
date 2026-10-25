---
title: "Watermark"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar en textvattenstämpel."
type: docs
weight: 37
url: /sv/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Representerar ett textvattenmärke. För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


Klassen Watermark representerar ett textvattenmärke i GroupDocs.Viewer-komponenten.
Den används för att definiera och applicera ett vattenmärke på dokumentens renderade utdata.


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
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Initierar en ny instans av |
Watermark
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Returnerar vattenmärketexten. |
|
|  | [getColor()](#getColor--) | Returnerar vattenmärkesfärgen. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Returnerar vattenmärkesfärgen i hex-format. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Ställer in vattenmärkesfärgen. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Ställer in vattenmärkesfärgen. |
|
|  | [getPosition()](#getPosition--) | Returnerar vattenmärkespositionen. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Ställer in vattenmärkespositionen. |
|
|  | [getSize()](#getSize--) | Returnerar vattenmärkesstorleken. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Ställer in vattenstämpelns storlek. |
|
|  | [getFontName()](#getFontName--) | Returnerar teckensnittets namn som används för vattenstämpeln. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Ställer in teckensnittets namn som används för vattenstämpeln. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initierar en ny instans av
Watermark
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Vattenstämpelns text. |
|

### getText() {#getText--}
```
public final String getText()
```


Returnerar vattenmärketexten.
Denna metod hämtar texten för vattenstämpeln som tillämpas på dokumentet.


**Returns:**
java.lang.String - vattenstämpelns text.

### getColor() {#getColor--}
```
public final Color getColor()
```


Returnerar vattenmärkesfärgen.
Denna metod hämtar färgen på vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - vattenstämpelns färg.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Returnerar vattenmärkesfärgen i hex-format.
Denna metod hämtar färgen på vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - vattenstämpelns färg i hex-format.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ställer in vattenmärkesfärgen.
Denna metod ställer in färgen på vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.awt.Color | Vattenstämpelns färg att ställa in. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Ställer in vattenmärkesfärgen.
Denna metod ställer in färgen på vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | colorName | java.lang.String | Vattenstämpelns färg att ställa in. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Returnerar vattenmärkespositionen.
Denna metod returnerar positionen för vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Ställer in vattenmärkespositionen.
Denna metod ställer in positionen för vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | Vattenstämpelns position. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Returnerar vattenmärkesstorleken.
Denna metod hämtar storleken på vattenstämpeln som tillämpas på dokumentet.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Ställer in vattenstämpelns storlek.
Denna metod ställer in storleken på vattenstämpeln som ska tillämpas på dokumentet.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | Vattenstämpelns storlek. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returnerar teckensnittets namn som används för vattenstämpeln.


**Returns:**
java.lang.String - teckensnittets namn som används för vattenstämpeln.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Ställer in teckensnittets namn som används för vattenstämpeln.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Teckensnittets namn som används för vattenstämpeln. |
|

