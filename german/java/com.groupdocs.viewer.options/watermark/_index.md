---
title: "Wasserzeichen"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt ein Textwasserzeichen dar."
type: docs
weight: 37
url: /de/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Stellt ein Textwasserzeichen dar. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


Die Watermark-Klasse stellt ein Textwasserzeichen in der GroupDocs.Viewer-Komponente dar.
Sie wird verwendet, um ein Wasserzeichen zu definieren und auf die gerenderte Ausgabe von Dokumenten anzuwenden.


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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Initialisiert eine neue Instanz von |
Wasserzeichen
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Gibt den Wasserzeichen-Text zurück. |
|
|  | [getColor()](#getColor--) | Gibt die Farbe des Wasserzeichens zurück. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Gibt die Farbe des Wasserzeichens im Hex-Format zurück. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Setzt die Farbe des Wasserzeichens. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Setzt die Farbe des Wasserzeichens. |
|
|  | [getPosition()](#getPosition--) | Gibt die Position des Wasserzeichens zurück. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Setzt die Position des Wasserzeichens. |
|
|  | [getSize()](#getSize--) | Gibt die Größe des Wasserzeichens zurück. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Setzt die Größe des Wasserzeichens. |
|
|  | [getFontName()](#getFontName--) | Gibt den für das Wasserzeichen verwendeten Schriftartnamen zurück. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Setzt den für das Wasserzeichen verwendeten Schriftartnamen. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initialisiert eine neue Instanz von
Wasserzeichen
Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Der Wasserzeichen-Text. |
|

### getText() {#getText--}
```
public final String getText()
```


Gibt den Wasserzeichen-Text zurück.
Diese Methode ruft den Text des auf das Dokument angewendeten Wasserzeichens ab.


**Returns:**
java.lang.String - der Wasserzeichen-Text.

### getColor() {#getColor--}
```
public final Color getColor()
```


Gibt die Farbe des Wasserzeichens zurück.
Diese Methode ruft die Farbe des auf das Dokument angewendeten Wasserzeichens ab.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - die Wasserzeichenfarbe.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Gibt die Farbe des Wasserzeichens im Hex-Format zurück.
Diese Methode ruft die Farbe des auf das Dokument angewendeten Wasserzeichens ab.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - die Wasserzeichenfarbe im Hex-Format.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Setzt die Farbe des Wasserzeichens.
Diese Methode legt die Farbe des auf das Dokument angewendeten Wasserzeichens fest.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.awt.Color | Die zu setzende Wasserzeichenfarbe. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Setzt die Farbe des Wasserzeichens.
Diese Methode legt die Farbe des auf das Dokument angewendeten Wasserzeichens fest.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | colorName | java.lang.String | Die zu setzende Wasserzeichenfarbe. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Gibt die Position des Wasserzeichens zurück.
Diese Methode gibt die Position des auf das Dokument angewendeten Wasserzeichens zurück.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Setzt die Position des Wasserzeichens.
Diese Methode legt die Position des auf das Dokument angewendeten Wasserzeichens fest.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | Die Wasserzeichenposition. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Gibt die Größe des Wasserzeichens zurück.
Diese Methode ruft die Größe des auf das Dokument angewendeten Wasserzeichens ab.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Setzt die Größe des Wasserzeichens.
Diese Methode legt die Größe des auf das Dokument anzuwendenden Wasserzeichens fest.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | Die Wasserzeichengröße. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Gibt den für das Wasserzeichen verwendeten Schriftartnamen zurück.


**Returns:**
java.lang.String - der für das Wasserzeichen verwendete Schriftname.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Setzt den für das Wasserzeichen verwendeten Schriftartnamen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der für das Wasserzeichen verwendete Schriftname. |
|

