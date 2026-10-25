---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt weergave‑informatie voor een PDF‑document voor."
type: docs
weight: 24
url: /nl/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Stelt weergave‑informatie voor een PDF‑document voor.


De PdfViewInfo interface definieert het contract voor het benaderen en manipuleren van weergave-informatie
voor een PDF-document in de GroupDocs.Viewer component. Het biedt methoden om informatie op te halen
zoals het toestaan van afdrukken en andere eigenschappen.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | Controleert of afdrukken van het document is toegestaan. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Stelt in of afdrukken van het document is toegestaan. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Controleert of afdrukken van het document is toegestaan.


**Returns:**
boolean -  true  als afdrukken is toegestaan,  false  anders.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Stelt in of afdrukken van het document is toegestaan.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | allowPrinting | boolean | true  om afdrukken toe te staan,  false  anders. |
|

