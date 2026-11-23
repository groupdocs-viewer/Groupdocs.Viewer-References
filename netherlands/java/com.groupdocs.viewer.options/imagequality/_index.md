---
title: "ImageQuality"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "De kwaliteit van afbeeldingen in de uitvoer‑HTML die in de PDF‑documenten staat."
type: docs
weight: 41
url: /nl/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

De kwaliteit van afbeeldingen in de uitvoer‑HTML die in de PDF‑documenten staat.


De ImageQuality‑enum vertegenwoordigt de kwaliteit van afbeeldingen in de uitvoer‑HTML die in de PDF‑documenten zit.
in de GroupDocs.Viewer‑component. Het biedt verschillende niveaus van afbeeldingskwaliteit die kunnen worden gebruikt
om de weergave en compressie van afbeeldingen in de gegenereerde HTML‑output te regelen.


Voorbeeldgebruik:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [LOW](#LOW) | De aanvaardbare kwaliteit en beste prestaties. |
|
|  | [MEDIUM](#MEDIUM) | Betere kwaliteit en tragere prestaties. |
|
|  | [HIGH](#HIGH) | De beste kwaliteit maar trage prestaties. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


De aanvaardbare kwaliteit en beste prestaties.
Deze instelling geeft de weergavesnelheid prioriteit boven de beeldkwaliteit.


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Betere kwaliteit en tragere prestaties.
Deze instelling biedt een evenwicht tussen beeldkwaliteit en weergavesnelheid.


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


De beste kwaliteit maar trage prestaties.
Deze instelling geeft de beeldkwaliteit prioriteit boven de weergavesnelheid.


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
| name | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
