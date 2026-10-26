---
title: "ImageQuality"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "La qualità delle immagini nell'HTML di output contenuto nei documenti PDF."
type: docs
weight: 41
url: /it/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

La qualità delle immagini nell'HTML di output contenuto nei documenti PDF.

L'enumerazione ImageQuality rappresenta la qualità delle immagini nell'HTML di output contenuto nei documenti PDF nel componente GroupDocs.Viewer. Fornisce diversi livelli di qualità dell'immagine che possono essere usati per controllare il rendering e la compressione delle immagini nell'output HTML generato.

Esempio di utilizzo:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [LOW](#LOW) | La qualità accettabile e le migliori prestazioni. |
| [MEDIUM](#MEDIUM) | Qualità migliore e prestazioni più lente. |
| [HIGH](#HIGH) | La migliore qualità ma prestazioni lente. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


La qualità accettabile e le migliori prestazioni. Questa impostazione privilegia la velocità di rendering rispetto alla qualità dell'immagine.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Qualità migliore e prestazioni più lente. Questa impostazione offre un equilibrio tra la qualità dell'immagine e la velocità di rendering.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


La migliore qualità ma prestazioni lente. Questa impostazione privilegia la qualità dell'immagine rispetto alla velocità di rendering.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
