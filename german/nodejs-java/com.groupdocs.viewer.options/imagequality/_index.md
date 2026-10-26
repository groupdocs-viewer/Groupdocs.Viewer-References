---
title: "ImageQuality"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Die Bildqualität im ausgegebenen HTML, das in den PDF-Dokumenten enthalten ist."
type: docs
weight: 41
url: /de/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Die Bildqualität im ausgegebenen HTML, das in den PDF-Dokumenten enthalten ist.

Das ImageQuality‑Enum stellt die Qualität von Bildern im Ausgabe‑HTML dar, das in den PDF‑Dokumenten der GroupDocs.Viewer‑Komponente enthalten ist. Es bietet verschiedene Qualitätsstufen, die zur Steuerung der Darstellung und Kompression von Bildern im erzeugten HTML‑Ausgabe verwendet werden können.

Beispielhafte Verwendung:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [LOW](#LOW) | Die akzeptable Qualität und beste Leistung. |
| [MEDIUM](#MEDIUM) | Bessere Qualität und langsamere Leistung. |
| [HIGH](#HIGH) | Die beste Qualität, aber langsame Leistung. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Die akzeptable Qualität und beste Leistung. Diese Einstellung priorisiert die Rendering‑Geschwindigkeit gegenüber der Bildqualität.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Bessere Qualität und langsamere Leistung. Diese Einstellung bietet ein Gleichgewicht zwischen Bildqualität und Rendering‑Geschwindigkeit.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Die beste Qualität, aber langsame Leistung. Diese Einstellung priorisiert die Bildqualität gegenüber der Rendering‑Geschwindigkeit.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
