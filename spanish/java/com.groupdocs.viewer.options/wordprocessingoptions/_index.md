---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos de procesamiento de texto."
type: docs
weight: 38
url: /es/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Proporciona opciones para renderizar documentos de procesamiento de texto.


La clase WordProcessingOptions proporciona opciones para renderizar documentos de procesamiento de texto
en el componente GroupDocs.Viewer. Encapsula configuraciones y parámetros que pueden usarse
para controlar el proceso de renderizado y el formato de salida de los archivos de procesamiento de texto.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Ejemplo de uso:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Inicializa una nueva instancia de la |
WordProcessingOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Obtiene el tamaño de página para renderizar archivos HTM y HTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Establece el tamaño de página para renderizar archivos HTM y HTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indica si la renderización de cambios rastreados (revisiones) está habilitada. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Establece si la renderización de cambios rastreados (revisiones) está habilitada. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Obtiene el margen izquierdo de página para la renderización HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Establece el margen izquierdo de página para la renderización HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | Obtiene el margen derecho de página para la renderización HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Establece el margen derecho de la página para la renderización HTML. |
|
|  | [getTopMargin()](#getTopMargin--) | Obtiene el margen superior de la página para la renderización HTML. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Establece el margen superior de la página para la renderización HTML. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Margen inferior de la página (solo para renderización HTML) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Establece el margen inferior de la página para la renderización HTML. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o en cirílico. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o en cirílico. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indica si la navegación del índice debe desactivarse al renderizar a HTML o PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Establece si la navegación del índice debe desactivarse al renderizar a HTML o PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Obtiene un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento de procesamiento de texto de entrada a los formatos de salida HTML, PDF, PNG o JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Establece un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento de procesamiento de texto de entrada a los formatos de salida HTML, PDF, PNG o JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene la resolución horizontal de las imágenes generadas en puntos por pulgada. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Establece la resolución horizontal para las imágenes generadas en puntos por pulgada. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Obtiene la resolución vertical de las imágenes generadas en puntos por pulgada. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Establece la resolución vertical para las imágenes generadas en puntos por pulgada. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Permite aplicar forzadamente la numeración de páginas para el documento de procesamiento de texto cargado. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Permite aplicar forzadamente la numeración de páginas para el documento de procesamiento de texto cargado. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Verifique si las opciones han cambiado. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Inicializa una nueva instancia de la
WordProcessingOptions
clase.
Contiene opciones para renderizar documentos de procesamiento de texto. Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Obtiene el tamaño de página para renderizar archivos HTM y HTML.


Al usar el tamaño de página predeterminado, es posible que parte del contenido no quepa en el marco de la página.
Para ajustar el contenido, puede establecer un tamaño de página mayor, como A3, usando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Establece el tamaño de página para renderizar archivos HTM y HTML.


Al usar el tamaño de página predeterminado, es posible que parte del contenido no quepa en el marco de la página.
Para ajustar el contenido, puede establecer un tamaño de página mayor, como A3, usando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | El tamaño de la página de salida. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indica si la renderización de cambios rastreados (revisiones) está habilitada.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  si la renderización de cambios rastreados está habilitada,  false  en caso contrario.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Establece si la renderización de cambios rastreados (revisiones) está habilitada.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar la renderización de cambios rastreados,  false  para desactivarla. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Obtiene el margen izquierdo de página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - el valor del margen izquierdo de la página.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Establece el margen izquierdo de página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | El valor del margen izquierdo de la página a establecer. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Obtiene el margen derecho de página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - el valor del margen derecho de la página.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Establece el margen derecho de la página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | El valor del margen derecho de la página a establecer. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Obtiene el margen superior de la página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - el margen superior de la página.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Establece el margen superior de la página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | topMargin | java.lang.Double | El margen superior de la página a establecer. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Margen inferior de la página (solo para renderización HTML)
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - el margen inferior de la página.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Establece el margen inferior de la página para la renderización HTML.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | El margen inferior de la página a establecer. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o en cirílico.


**Returns:**
boolean - Verdadero si las funciones OpenType están habilitadas, falso de lo contrario.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o en cirílico.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | Verdadero para habilitar las funciones OpenType, falso de lo contrario. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indica si la navegación del índice debe deshabilitarse al renderizar a HTML o PDF. Cuando esta opción se establece en verdadero, para la renderización HTML, los enlaces relativos del índice se reemplazarán por etiquetas span, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, el índice se renderizará como texto plano sin enlaces.


**Returns:**
boolean - Verdadero si la navegación del índice está deshabilitada; de lo contrario, falso.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Establece si la navegación del índice debe deshabilitarse al renderizar a HTML o PDF. Cuando esta opción se establece en verdadero, para la renderización HTML, los enlaces relativos del índice se reemplazarán por etiquetas span, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, el índice se renderizará como texto plano sin enlaces.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Indica si la navegación del índice debe deshabilitarse. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Obtiene un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada en los formatos de salida HTML, PDF, PNG o JPEG. El valor predeterminado para esta propiedad es verdadero \\u2014 los campos se actualizarán antes de guardar.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Establece un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada en los formatos de salida HTML, PDF, PNG o JPEG. El valor predeterminado para esta propiedad es verdadero \\u2014 los campos se actualizarán antes de guardar.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Obtiene la resolución horizontal para las imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al renderizar documentos WordProcessing a formatos PNG o JPEG.


El valor predeterminado es 96 DPI. Valor mínimo posible: 72 DPI, valor máximo posible: 600 DPI.
Si el valor especificado por el usuario está fuera de estos límites, se aplicará el valor mínimo o máximo posible.


**Returns:**
int - la resolución horizontal en DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Establece la resolución horizontal para las imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al renderizar documentos WordProcessing a formatos PNG o JPEG.


El valor predeterminado es 96 DPI. Valor mínimo posible: 72 DPI, valor máximo posible: 600 DPI.
Si el valor especificado por el usuario está fuera de estos límites, se aplicará el valor mínimo o máximo posible.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | horizontalResolution | int | la resolución horizontal en DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Obtiene la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al renderizar documentos WordProcessing a formatos PNG o JPEG.


El valor predeterminado es 96 DPI. Valor mínimo posible: 72 DPI, valor máximo posible: 600 DPI.
Si el valor especificado por el usuario está fuera de estos límites, se aplicará el valor mínimo o máximo posible.


**Returns:**
int - la resolución vertical en DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Establece la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al renderizar documentos WordProcessing a formatos PNG o JPEG.


El valor predeterminado es 96 DPI. Valor mínimo posible: 72 DPI, valor máximo posible: 600 DPI.
Si el valor especificado por el usuario está fuera de estos límites, se aplicará el valor mínimo o máximo posible.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | verticalResolution | int | la resolución vertical en DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Permite aplicar forzosamente la numeración de páginas para el documento WordProcessing cargado. Por defecto es [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 el documento permanece intacto.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Permite aplicar forzosamente la numeración de páginas para el documento WordProcessing cargado. Por defecto es [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 el documento permanece intacto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | la ubicación del número de página. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifique si las opciones han cambiado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | o | java.lang.Object | El objeto a comparar para igualdad. |
|

**Returns:**
boolean -  true  si las opciones son iguales al objeto especificado,  false  de lo contrario.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcula el valor del código hash para este objeto. El código hash se basa en
el estado interno del objeto y se utiliza en estructuras de datos basadas en hash
como mapas hash y conjuntos hash.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - el valor del código hash para este objeto.

