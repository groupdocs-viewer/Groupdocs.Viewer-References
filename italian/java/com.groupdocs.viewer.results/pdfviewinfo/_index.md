---
title: "PdfViewInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta le informazioni di visualizzazione per un documento PDF."
type: docs
weight: 24
url: /it/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un documento PDF.


L'interfaccia PdfViewInfo definisce il contratto per accedere e manipolare le informazioni di visualizzazione
per un documento PDF nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni
come la possibilità di stampa e altre proprietà.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | Verifica se la stampa del documento è consentita. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Imposta se la stampa del documento è consentita. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Verifica se la stampa del documento è consentita.


**Returns:**
boolean -  true  se la stampa è consentita,  false  altrimenti.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Imposta se la stampa del documento è consentita.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | allowPrinting | boolean | true  per consentire la stampa,  false  altrimenti. |
|

