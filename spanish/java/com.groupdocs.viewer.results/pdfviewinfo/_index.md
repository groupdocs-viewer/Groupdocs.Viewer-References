---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa información de vista para un documento PDF."
type: docs
weight: 24
url: /es/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Representa información de vista para un documento PDF.


La interfaz PdfViewInfo define el contrato para acceder y manipular la información de la vista
para un documento PDF en el componente GroupDocs.Viewer. Proporciona métodos para recuperar información
como permitir la impresión y otras propiedades.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | Comprueba si la impresión del documento está permitida. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Establece si se permite la impresión del documento. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Comprueba si la impresión del documento está permitida.


**Returns:**
boolean -  true  si se permite la impresión,  false  de lo contrario.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Establece si se permite la impresión del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | allowPrinting | boolean | true  para permitir la impresión,  false  de lo contrario. |
|

