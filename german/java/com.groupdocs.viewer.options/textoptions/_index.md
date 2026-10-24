---
title: "TextOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Optionen zum Aufteilen von Textdateien in Seiten."
type: docs
weight: 32
url: /de/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Optionen zum Aufteilen von Textdateien in Seiten.


Die TextOptions-Klasse bietet Optionen zum Aufteilen von Textdateien in Seiten in der GroupDocs.Viewer-Komponente.
Sie ermöglicht es Ihnen, zu steuern, wie Textdateien zu einzelnen Seiten für Rendering- und Anzeigezwecke aufgeteilt werden.


Beispielverwendung:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Initialisiert eine neue Instanz von |
TextOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Ermittelt die maximale Anzahl von Zeichen pro Zeile auf einer Seite. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Legt die maximale Anzahl von Zeichen pro Zeile auf einer Seite fest. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Ermittelt die maximale Anzahl von Zeilen pro Seite. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Legt die maximale Anzahl von Zeilen pro Seite fest. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initialisiert eine neue Instanz von
TextOptions
Klasse.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Ermittelt die maximale Anzahl von Zeichen pro Zeile auf einer Seite.


***Note:** The default value is 85.*
Der Standardwert ist 85. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int – die maximale Anzahl von Zeichen pro Zeile auf einer Seite.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Legt die maximale Anzahl von Zeichen pro Zeile auf einer Seite fest.


***Note:** The default value is 85.*
Der Standardwert ist 85. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxCharsPerRow | int | Die maximale Anzahl von Zeichen pro Zeile auf einer Seite. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Ermittelt die maximale Anzahl von Zeilen pro Seite.


***Note:** The default value is 55.*
Der Standardwert ist 55. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int – die maximale Anzahl von Zeilen.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Legt die maximale Anzahl von Zeilen pro Seite fest.


***Note:** The default value is 55.*
Der Standardwert ist 55. Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxRowsPerPage | int | Die maximale Anzahl von Zeilen. |
|

