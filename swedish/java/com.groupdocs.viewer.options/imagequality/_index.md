---
title: "ImageQuality"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Kvaliteten på bilder i den genererade HTML som finns i PDF-dokumenten."
type: docs
weight: 41
url: /sv/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Kvaliteten på bilder i den genererade HTML som finns i PDF-dokumenten.


ImageQuality‑enumet representerar bildkvaliteten i den genererade HTML‑utdata som finns i PDF‑dokumenten
i GroupDocs.Viewer‑komponenten. Den tillhandahåller olika nivåer av bildkvalitet som kan användas
för att kontrollera rendering och komprimering av bilder i den genererade HTML‑utdata.


Exempel på användning:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [LOW](#LOW) | Den acceptabla kvaliteten och bästa prestanda. |
|
|  | [MEDIUM](#MEDIUM) | Bättre kvalitet och långsammare prestanda. |
|
|  | [HIGH](#HIGH) | Den bästa kvaliteten men långsam prestanda. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Den acceptabla kvaliteten och bästa prestanda.
Denna inställning prioriterar renderingshastighet framför bildkvalitet.


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Bättre kvalitet och långsammare prestanda.
Denna inställning ger en balans mellan bildkvalitet och renderingshastighet.


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Den bästa kvaliteten men långsam prestanda.
Denna inställning prioriterar bildkvalitet framför renderingshastighet.


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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
