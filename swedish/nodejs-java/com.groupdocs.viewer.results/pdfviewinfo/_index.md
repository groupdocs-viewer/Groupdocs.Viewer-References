---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar vyinformation för ett PDF-dokument."
type: docs
weight: 22
url: /sv/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Representerar vyinformation för ett PDF-dokument.

PdfViewInfo-gränssnittet definierar kontraktet för att komma åt och manipulera vyinformation för ett PDF-dokument i GroupDocs.Viewer-komponenten. Det tillhandahåller metoder för att hämta information såsom möjliggörande av utskrift och andra egenskaper.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Kontrollerar om utskrift av dokumentet är tillåten. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Ställer in om utskrift av dokumentet är tillåten. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Kontrollerar om utskrift av dokumentet är tillåten.

**Returns:**
boolean -  true  om utskrift är tillåten,  false  annars.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Ställer in om utskrift av dokumentet är tillåten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowPrinting | boolean | true  för att tillåta utskrift,  false  annars. |

