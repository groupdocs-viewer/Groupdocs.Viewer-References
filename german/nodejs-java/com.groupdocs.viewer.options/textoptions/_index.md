---
title: "TextOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Optionen zum Aufteilen von Textdateien in Seiten."
type: docs
weight: 32
url: /de/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Optionen zum Aufteilen von Textdateien in Seiten.

Die TextOptions-Klasse bietet Optionen zum Aufteilen von Textdateien in Seiten in der GroupDocs.Viewer-Komponente. Sie ermöglicht die Kontrolle darüber, wie Textdateien für Rendering- und Anzeigezwecke in einzelne Seiten unterteilt werden.

Beispielhafte Verwendung:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextOptions()](#TextOptions--) | Initialisiert eine neue Instanz der  TextOptions  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Ermittelt die maximale Anzahl von Zeichen pro Zeile auf einer Seite. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Legt die maximale Anzahl von Zeichen pro Zeile auf einer Seite fest. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Ermittelt die maximale Anzahl von Zeilen pro Seite. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Legt die maximale Anzahl von Zeilen pro Seite fest. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initialisiert eine neue Instanz der  TextOptions  Klasse.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Ermittelt die maximale Anzahl von Zeichen pro Zeile auf einer Seite.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - die maximale Anzahl von Zeichen pro Zeile auf einer Seite.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Legt die maximale Anzahl von Zeichen pro Zeile auf einer Seite fest.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxCharsPerRow | int | Die maximale Anzahl von Zeichen pro Zeile auf einer Seite. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Ermittelt die maximale Anzahl von Zeilen pro Seite.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - die maximale Anzahl von Zeilen.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Legt die maximale Anzahl von Zeilen pro Seite fest.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxRowsPerPage | int | Die maximale Anzahl von Zeilen. |

