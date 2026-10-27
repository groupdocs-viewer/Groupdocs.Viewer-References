---
title: "ImageQuality"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "De kwaliteit van afbeeldingen in de gegenereerde HTML die door de PDF-documenten wordt geleverd."
type: docs
weight: 41
url: /nl/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

De kwaliteit van afbeeldingen in de gegenereerde HTML die door de PDF-documenten wordt geleverd.

De ImageQuality‑enum vertegenwoordigt de kwaliteit van afbeeldingen in de uitvoer‑HTML die door de PDF‑documenten in de GroupDocs.Viewer‑component wordt gegenereerd. Het biedt verschillende niveaus van afbeeldingskwaliteit die kunnen worden gebruikt om de weergave en compressie van afbeeldingen in de gegenereerde HTML‑uitvoer te regelen.

Voorbeeldgebruik:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [LOW](#LOW) | De acceptabele kwaliteit en beste prestaties. |
| [MEDIUM](#MEDIUM) | Betere kwaliteit en tragere prestaties. |
| [HIGH](#HIGH) | De beste kwaliteit maar trage prestaties. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


De acceptabele kwaliteit en beste prestaties. Deze instelling geeft prioriteit aan weergavesnelheid boven afbeeldingskwaliteit.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Betere kwaliteit en tragere prestaties. Deze instelling biedt een balans tussen afbeeldingskwaliteit en weergavesnelheid.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


De beste kwaliteit maar trage prestaties. Deze instelling geeft prioriteit aan afbeeldingskwaliteit boven weergavesnelheid.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
