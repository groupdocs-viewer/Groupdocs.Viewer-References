---
title: "PdfViewInfo"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa información de vista para un documento PDF."
type: docs
weight: 22
url: /es/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Representa información de vista para un documento PDF.

La interfaz PdfViewInfo define el contrato para acceder y manipular la información de vista de un documento PDF en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como la habilitación de impresión y otras propiedades.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Comprueba si la impresión del documento está permitida. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Establece si la impresión del documento está permitida. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Comprueba si la impresión del documento está permitida.

**Returns:**
boolean -  true  si la impresión está permitida,  false  en caso contrario.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Establece si la impresión del documento está permitida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowPrinting | boolean | true  para permitir la impresión,  false  en caso contrario. |

