---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos en formato PDF."
type: docs
weight: 23
url: /es/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Proporciona opciones para renderizar documentos en formato PDF.


La clase PdfViewOptions encapsula configuraciones y parámetros adicionales.
que pueden usarse para controlar la renderización de documentos al formato PDF en el componente GroupDocs.Viewer.
Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


Ejemplo de uso:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Inicializa una nueva instancia de la |
PdfViewOptions
clase.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Inicializa una nueva instancia de la |
PdfViewOptions
clase.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Inicializa una nueva instancia de la clase  PdfViewOptions  . |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | Inicializa una nueva instancia de la clase  PdfViewOptions  con configuraciones predeterminadas. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Inicializa una nueva instancia de la |
PdfViewOptions
clase.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Inicializa una nueva instancia de la |
PdfViewOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Reduce el tamaño del archivo PDF de salida aplicando técnicas de optimización con diferentes opciones. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Reduce el tamaño del archivo PDF de salida aplicando técnicas de optimización con diferentes opciones. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Obtiene el ancho máximo de una imagen de salida en píxeles. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Establece el ancho máximo de una imagen de salida en píxeles. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Obtiene la altura máxima de una imagen de salida en píxeles. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Establece la altura máxima de una imagen de salida en píxeles. |
|
|  | [getImageWidth()](#getImageWidth--) | Obtiene el ancho de la imagen de salida en píxeles. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Establece el ancho de la imagen de salida en píxeles. |
|
|  | [getImageHeight()](#getImageHeight--) | Obtiene la altura de la imagen de salida en píxeles. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Establece la altura de la imagen de salida en píxeles. |
|
|  | [getSecurity()](#getSecurity--) | Obtiene las opciones de seguridad para el documento PDF de salida. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Establece las opciones de seguridad para el documento PDF de salida. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Obtiene la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Establece la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Inicializa una nueva instancia de la
PdfViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Inicializa una nueva instancia de la
PdfViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | El método utilizado para instanciar el flujo para escribir los datos del archivo de salida. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | El método utilizado para liberar el flujo creado por el método  createFileStream  . |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Inicializa una nueva instancia de la clase  PdfViewOptions  .


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | La fábrica que implementa métodos para crear y liberar el flujo del archivo de salida. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Inicializa una nueva instancia de la clase  PdfViewOptions  con configuraciones predeterminadas.


Este constructor crea un nuevo
PdfViewOptions
objeto con "output.pdf" como el formato de ruta de archivo para el archivo de salida.
El archivo de salida se colocará en el directorio de trabajo actual de la aplicación.
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Inicializa una nueva instancia de la
PdfViewOptions
clase.


Este constructor crea un nuevo
PdfViewOptions
objeto con el especificado
outputFilePath
parámetro
que representa la ruta del archivo PDF de salida.
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | La ruta del archivo PDF de salida. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Inicializa una nueva instancia de la
PdfViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | La ruta del archivo PDF de salida. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Reduce el tamaño del archivo PDF de salida aplicando técnicas de optimización con diferentes opciones.


Esta opción es compatible con cualquier formato de archivo de entrada que sea compatible con la conversión a PDF: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Para obtener detalles y ejemplos de código, consulte esta [página](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) y sus hijos.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Reduce el tamaño del archivo PDF de salida aplicando técnicas de optimización con diferentes opciones.


Esta opción es compatible con cualquier formato de archivo de entrada que sea compatible con la conversión a PDF: [Supported document formats](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Para obtener detalles y ejemplos de código, consulte esta [página](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) y sus hijos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | Objeto PdfOptimizationOptions o nulo. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Obtiene el ancho máximo de una imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad al renderizar una sola imagen a PDF. Para obtener detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - el ancho máximo de la imagen de salida en píxeles.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Establece el ancho máximo de una imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad al renderizar una sola imagen a PDF. Para obtener detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageMaxWidth | int | El ancho máximo de la imagen de salida en píxeles. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Obtiene la altura máxima de una imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad al renderizar una sola imagen a PDF. Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - la altura máxima de la imagen de salida en píxeles.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Establece la altura máxima de una imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad solo al renderizar una sola imagen a HTML. Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageMaxHeight | int | La altura máxima de la imagen de salida en píxeles. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Obtiene el ancho de la imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad al renderizar una sola imagen a PDF. Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - el ancho de la imagen de salida en píxeles.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Establece el ancho de la imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageWidth | int | El ancho de la imagen de salida en píxeles. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Obtiene la altura de la imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad solo al renderizar una sola imagen a HTML. Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - la altura de la imagen de salida en píxeles.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Establece la altura de la imagen de salida en píxeles. Este parámetro se aplica solo al convertir una sola imagen a HTML.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). GroupDocs.Viewer aplica esta propiedad solo al renderizar una sola imagen a HTML. Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Si establece esta propiedad, la propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageHeight | int | La altura de la imagen de salida en píxeles. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Obtiene las opciones de seguridad para el documento PDF de salida.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Establece las opciones de seguridad para el documento PDF de salida.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | Las opciones de seguridad para el documento PDF de salida. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Obtiene la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - la devolución de llamada para estimar el progreso de guardado del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Establece la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | La devolución de llamada para estimar el progreso de guardado del documento. |
|

