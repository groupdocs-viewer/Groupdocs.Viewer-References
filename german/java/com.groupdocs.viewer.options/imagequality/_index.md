---
title: "ImageQuality"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Die Qualität der Bilder im ausgegebenen HTML, das in den PDF-Dokumenten enthalten ist."
type: docs
weight: 41
url: /de/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Die Qualität der Bilder im ausgegebenen HTML, das in den PDF-Dokumenten enthalten ist.


Das ImageQuality‑Enum repräsentiert die Bildqualität im ausgegebenen HTML, das in den PDF‑Dokumenten enthalten ist.
in der GroupDocs.Viewer‑Komponente. Sie bietet verschiedene Qualitätsstufen für Bilder, die verwendet werden können.
zur Steuerung der Darstellung und Kompression von Bildern im erzeugten HTML‑Ausgabe.


Beispielverwendung:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [LOW](#LOW) | Die akzeptable Qualität und beste Leistung. |
|
|  | [MEDIUM](#MEDIUM) | Bessere Qualität und langsamere Leistung. |
|
|  | [HIGH](#HIGH) | Die beste Qualität, aber langsame Leistung. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Die akzeptable Qualität und beste Leistung.
Diese Einstellung priorisiert die Rendering‑Geschwindigkeit über die Bildqualität.


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Bessere Qualität und langsamere Leistung.
Diese Einstellung bietet ein Gleichgewicht zwischen Bildqualität und Rendering‑Geschwindigkeit.


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Die beste Qualität, aber langsame Leistung.
Diese Einstellung priorisiert die Bildqualität über die Rendering‑Geschwindigkeit.


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
