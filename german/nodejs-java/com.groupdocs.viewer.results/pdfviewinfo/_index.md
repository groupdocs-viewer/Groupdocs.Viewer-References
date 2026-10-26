---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Ansichtsinformationen für ein PDF‑Dokument dar."
type: docs
weight: 22
url: /de/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für ein PDF‑Dokument dar.

Das PdfViewInfo-Interface definiert den Vertrag zum Zugreifen und Manipulieren von Ansichtsinformationen für ein PDF-Dokument in der GroupDocs.Viewer-Komponente. Es stellt Methoden zum Abrufen von Informationen wie dem Erlauben des Druckens und anderen Eigenschaften bereit.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Prüft, ob das Drucken des Dokuments erlaubt ist. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Legt fest, ob das Drucken des Dokuments erlaubt ist. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Prüft, ob das Drucken des Dokuments erlaubt ist.

**Returns:**
boolean -  true  wenn das Drucken erlaubt ist,  false  sonst.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Legt fest, ob das Drucken des Dokuments erlaubt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowPrinting | boolean | true  um das Drucken zu erlauben,  false  sonst. |

