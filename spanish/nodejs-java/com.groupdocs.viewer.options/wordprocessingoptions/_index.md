---
title: "WordProcessingOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar documentos de procesamiento de texto."
type: docs
weight: 38
url: /es/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Proporciona opciones para renderizar documentos de procesamiento de texto.

La clase WordProcessingOptions proporciona opciones para renderizar documentos de procesamiento de texto en el componente GroupDocs.Viewer. Encapsula configuraciones y parámetros que pueden usarse para controlar el proceso de renderizado y el formato de salida de los archivos de procesamiento de texto. Para más detalles, consulte la [documentation][].

Ejemplo de uso:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Inicializa una nueva instancia de la clase  WordProcessingOptions . |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageSize()](#getPageSize--) | Obtiene el tamaño de página para renderizar archivos HTM y HTML. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Establece el tamaño de página para renderizar archivos HTM y HTML. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indica si el renderizado de cambios rastreados (revisiones) está habilitado. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Establece si el renderizado de cambios rastreados (revisiones) está habilitado. |
| [getLeftMargin()](#getLeftMargin--) | Obtiene el margen izquierdo de la página para el renderizado HTML. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Establece el margen izquierdo de la página para el renderizado HTML. |
| [getRightMargin()](#getRightMargin--) | Obtiene el margen derecho de la página para el renderizado HTML. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Establece el margen derecho de la página para el renderizado HTML. |
| [getTopMargin()](#getTopMargin--) | Obtiene el margen superior de la página para el renderizado HTML. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Establece el margen superior de la página para la renderización HTML. |
| [getBottomMargin()](#getBottomMargin--) | Margen inferior de la página (solo para renderización HTML) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Establece el margen inferior de la página para la renderización HTML. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o cirílico. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o cirílico. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indica si la navegación del índice debe desactivarse al renderizar a HTML o PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Establece si la navegación del índice debe desactivarse al renderizar a HTML o PDF. |
| [isUpdateFields()](#isUpdateFields--) | Obtiene un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada en los formatos de salida HTML, PDF, PNG o JPEG. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Establece un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada en los formatos de salida HTML, PDF, PNG o JPEG. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si las opciones han cambiado. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Inicializa una nueva instancia de la clase WordProcessingOptions. Contiene opciones para renderizar documentos de procesamiento de texto. Para más detalles, vea la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Obtiene el tamaño de página para renderizar archivos HTM y HTML.

Al usar el tamaño de página predeterminado, es posible que parte del contenido no quepa en el marco de la página. Para ajustar el contenido, puede establecer un tamaño de página mayor, como A3, usando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Establece el tamaño de página para renderizar archivos HTM y HTML.

Al usar el tamaño de página predeterminado, es posible que parte del contenido no quepa en el marco de la página. Para ajustar el contenido, puede establecer un tamaño de página mayor, como A3, usando [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | El tamaño de la página de salida. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indica si el renderizado de cambios rastreados (revisiones) está habilitado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  si la renderización de cambios controlados está habilitada,  false  en caso contrario.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Establece si el renderizado de cambios rastreados (revisiones) está habilitado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar la renderización de cambios controlados,  false  para deshabilitarla. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Obtiene el margen izquierdo de la página para el renderizado HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - el valor del margen izquierdo de la página.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Establece el margen izquierdo de la página para el renderizado HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftMargin | java.lang.Double | El valor del margen izquierdo de la página a establecer. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Obtiene el margen derecho de la página para el renderizado HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - el valor del margen derecho de la página.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Establece el margen derecho de la página para el renderizado HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rightMargin | java.lang.Double | El valor del margen derecho de la página a establecer. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Obtiene el margen superior de la página para el renderizado HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - el margen superior de la página.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Establece el margen superior de la página para la renderización HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| topMargin | java.lang.Double | El margen superior de la página a establecer. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Margen inferior de la página (solo para renderización HTML)

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - el margen inferior de la página.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Establece el margen inferior de la página para la renderización HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bottomMargin | java.lang.Double | El margen inferior de la página a establecer. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o cirílico.

**Returns:**
boolean -  True  si las funciones OpenType están habilitadas, false en caso contrario.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Esta opción habilita el kerning y otras funciones OpenType al renderizar scripts árabes, hebreos, indios, basados en latín o cirílico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | True para habilitar las funciones OpenType, false en caso contrario. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indica si la navegación del índice debe deshabilitarse al renderizar a HTML o PDF. Cuando esta opción se establece en true, para la renderización HTML, los enlaces relativos del índice se reemplazarán con etiquetas span, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, el índice se renderizará como texto plano sin enlaces.

**Returns:**
boolean - True si la navegación del índice está deshabilitada; de lo contrario, false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Establece si la navegación del índice debe deshabilitarse al renderizar a HTML o PDF. Cuando esta opción se establece en true, para la renderización HTML, los enlaces relativos del índice se reemplazarán con etiquetas span, eliminando la funcionalidad pero conservando la apariencia visual. Para la renderización PDF, el índice se renderizará como texto plano sin enlaces.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Indica si la navegación del índice debe deshabilitarse. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Obtiene un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada a los formatos de salida HTML, PDF, PNG o JPEG. El valor predeterminado para esta propiedad es true \\u2014 los campos se actualizarán antes de guardar.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Establece un valor que determina si los campos de ciertos tipos deben actualizarse antes de guardar el documento WordProcessing de entrada a los formatos de salida HTML, PDF, PNG o JPEG. El valor predeterminado para esta propiedad es true \\u2014 los campos se actualizarán antes de guardar.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si las opciones han cambiado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El objeto a comparar para igualdad. |

**Returns:**
boolean -  true si las opciones son iguales al objeto especificado,  false en caso contrario.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcula el valor del código hash para este objeto. El código hash se basa en el estado interno del objeto y se utiliza en estructuras de datos basadas en hash, como mapas hash y conjuntos hash.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - el valor del código hash para este objeto.
