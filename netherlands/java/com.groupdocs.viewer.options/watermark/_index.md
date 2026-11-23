---
title: "Watermark"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt een tekstwatermerk voor."
type: docs
weight: 37
url: /nl/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Stelt een tekstwatermerk voor. Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


De Watermark-klasse vertegenwoordigt een tekstwatermerk in de GroupDocs.Viewer-component.
Het wordt gebruikt om een watermerk te definiëren en toe te passen op de gerenderde uitvoer van documenten.


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
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
Watermark
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Retourneert de watermerktekst. |
|
|  | [getColor()](#getColor--) | Retourneert de watermerk-kleur. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Retourneert de watermerk-kleur in hex-formaat. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Stelt de watermerk-kleur in. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Stelt de watermerk-kleur in. |
|
|  | [getPosition()](#getPosition--) | Retourneert de watermerk-positie. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Stelt de watermerk-positie in. |
|
|  | [getSize()](#getSize--) | Retourneert de watermerk-grootte. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Stelt de grootte van het watermerk in. |
|
|  | [getFontName()](#getFontName--) | Retourneert de naam van het lettertype dat voor het watermerk wordt gebruikt. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Stelt de naam van het lettertype in dat voor het watermerk wordt gebruikt. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initialiseert een nieuw exemplaar van de
Watermark
klasse.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | De tekst van het watermerk. |
|

### getText() {#getText--}
```
public final String getText()
```


Retourneert de watermerktekst.
Deze methode haalt de tekst op van het watermerk dat op het document is toegepast.


**Returns:**
java.lang.String - de watermerktekst.

### getColor() {#getColor--}
```
public final Color getColor()
```


Retourneert de watermerk-kleur.
Deze methode haalt de kleur op van het watermerk dat op het document is toegepast.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - de watermerk kleur.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Retourneert de watermerk-kleur in hex-formaat.
Deze methode haalt de kleur op van het watermerk dat op het document is toegepast.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - de watermerk kleur in hex-formaat.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Stelt de watermerk-kleur in.
Deze methode stelt de kleur in van het watermerk dat op het document wordt toegepast.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.awt.Color | De in te stellen watermerk kleur. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Stelt de watermerk-kleur in.
Deze methode stelt de kleur in van het watermerk dat op het document wordt toegepast.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | colorName | java.lang.String | De in te stellen watermerk kleur. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Retourneert de watermerk-positie.
Deze methode retourneert de positie van het watermerk dat op het document is toegepast.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Stelt de watermerk-positie in.
Deze methode stelt de positie in van het watermerk dat op het document wordt toegepast.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | De positie van het watermerk. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Retourneert de watermerk-grootte.
Deze methode haalt de grootte op van het watermerk dat op het document is toegepast.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Stelt de grootte van het watermerk in.
Deze methode stelt de grootte in van het watermerk dat op het document moet worden toegepast.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | De grootte van het watermerk. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Retourneert de naam van het lettertype dat voor het watermerk wordt gebruikt.


**Returns:**
java.lang.String - de naam van het lettertype dat voor het watermerk wordt gebruikt.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Stelt de naam van het lettertype in dat voor het watermerk wordt gebruikt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De naam van het lettertype dat voor het watermerk wordt gebruikt. |
|

