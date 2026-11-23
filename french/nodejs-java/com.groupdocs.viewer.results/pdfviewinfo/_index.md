---
title: "PdfViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente les informations de vue pour un document PDF."
type: docs
weight: 22
url: /fr/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Représente les informations de vue pour un document PDF.

L'interface PdfViewInfo définit le contrat pour accéder et manipuler les informations de vue d'un document PDF dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles que l'autorisation d'impression et d'autres propriétés.

Exemple d'utilisation :

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Méthodes

| Méthode | Description |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Vérifie si l'impression du document est autorisée. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Définit si l'impression du document est autorisée. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Vérifie si l'impression du document est autorisée.

**Returns:**
boolean -  true  si l'impression est autorisée,  false  sinon.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Définit si l'impression du document est autorisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowPrinting | boolean | true  pour autoriser l'impression,  false  sinon. |

