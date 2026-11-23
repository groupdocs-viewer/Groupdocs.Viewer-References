---
title: "Size"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Enthält die Wasserzeichen‑Größe."
type: docs
weight: 30
url: /de/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Enthält die Wasserzeichen‑Größe.

Die Size‑Klasse repräsentiert die Größe eines Wasserzeichens in der GroupDocs.Viewer‑Komponente. Sie bietet Optionen zum Festlegen der Abmessungen des Wasserzeichens, wie Breite und Höhe.

Beispielhafte Verwendung:

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Initialisiert eine neue Instanz der Size‑Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Stellt die maximale Größe des Wasserzeichentextes dar, die auf die Seite passt. |
| [HALF_SIZE](#HALF-SIZE) | Stellt die Hälfte der maximalen Größe des Wasserzeichentextes dar, die auf die Seite passt. |
| [ONE_THIRD](#ONE-THIRD) | Stellt ein Drittel der maximalen Größe des Wasserzeichentextes dar, die auf die Seite passt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Gibt die Größe des Wasserzeichentextes in Prozent in Relation zur Seitenbreite zurück. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Initialisiert eine neue Instanz der Size‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| relativeSize | byte | Die Größe in Prozent in Relation zur Seitengröße. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Stellt die maximale Größe des Wasserzeichentextes dar, die auf die Seite passt.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Stellt die Hälfte der maximalen Größe des Wasserzeichentextes dar, die auf die Seite passt.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Stellt ein Drittel der maximalen Größe des Wasserzeichentextes dar, die auf die Seite passt.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Gibt die Größe des Wasserzeichentextes in Prozent in Relation zur Seitenbreite zurück.

**Returns:**
byte – die Größe des Wasserzeichentextes in Prozent.
