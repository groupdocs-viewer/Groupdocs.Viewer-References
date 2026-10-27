---
title: "PdfOptimizationOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Utilice esta clase para especificar opciones de optimización PDF que se aplicarán al archivo PDF de salida."
type: docs
weight: 21
url: /es/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Utilice esta clase para especificar opciones de optimización PDF que se aplicarán al archivo PDF de salida.

Estas opciones de optimización son compatibles con cualquier formato de archivo de entrada que sea compatible con la exportación a PDF. Para más detalles y ejemplos de código, consulte esta [página][] y sus elementos secundarios.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Establece los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isLinearize()](#isLinearize--) | Habilita la optimización del archivo PDF de salida para su visualización en línea con un navegador web. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Establece si se debe optimizar el PDF de salida para la navegación en línea con un navegador web. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Las anotaciones pueden eliminarse cuando no son necesarias. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Establece si se deben eliminar las anotaciones innecesarias del PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Si el documento PDF contiene AcroForms, podemos intentar reducir el tamaño del archivo aplanando los campos de formulario. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Establece si se deben eliminar los campos de formulario del PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | El archivo PDF está compuesto de Texto, Imagen, Adjuntos, Anotaciones, Gráficos y otros objetos. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Establece si se debe convertir el PDF a escala de grises. |
| [isSubsetFonts()](#isSubsetFonts--) | Cada fuente utilizada para mostrar texto en la página contiene un conjunto de glifos para los caracteres de la fuente. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Establece si se deben crear subconjuntos de las fuentes en el PDF. |
| [isCompressImages()](#isCompressImages--) | Si el archivo PDF de origen contiene imágenes, considere comprimir las imágenes y establecer su calidad. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Establece si se deben comprimir las imágenes en el PDF. |
| [getImageQuality()](#getImageQuality--) | Si el archivo PDF de origen contiene imágenes, considere comprimir las imágenes y establecer su calidad. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Establece la calidad de imagen para comprimir las imágenes en el PDF. |
| [isResizeImages()](#isResizeImages--) | Puede usarse con la opción CompressImages para redimensionar las imágenes con una resolución más baja. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Establece si se deben redimensionar las imágenes en el PDF. |
| [getMaxResolution()](#getMaxResolution--) | Puede usarse con la opción CompressImages para redimensionar las imágenes con una resolución más baja. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Establece la resolución máxima para redimensionar las imágenes en el PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimiza los bordes y fuentes de las hojas de cálculo de Excel para un tamaño de archivo de salida más pequeño. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Establece si se deben optimizar las hojas de cálculo en el PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Elimina la información privada (información de pieza de página) si está configurado como verdadero. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Establece si se debe eliminar la información privada del PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | Si el documento usa fuentes incrustadas, significa que todos los datos de la fuente están incluidos en el documento. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Establece si se deben desincorporar las fuentes incrustadas en el PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | A veces un documento contiene varios flujos de recursos idénticos (por ejemplo, imágenes). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Establece si se deben enlazar los flujos duplicados en el PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Si esta propiedad está configurada como verdadera, el contenido de la página se reutilizará al optimizar el documento para páginas idénticas. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Establece si se permite reutilizar el contenido de la página en el PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | A veces un documento contiene flujos de recursos sin usar. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Establece si se deben eliminar los flujos sin usar del PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Un documento PDF a veces contiene objetos PDF que no están referenciados por ningún otro objeto en el documento. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Establece si se deben eliminar los objetos sin usar del PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Establece los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100.

Para obtener detalles y ejemplos de código, consulte esta [page][] y sus hijos.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Habilita la optimización del archivo PDF de salida para su visualización en línea con un navegador web.

Para un ejemplo de código, consulte esta [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  si el PDF de salida está optimizado para la navegación en línea,  false  de lo contrario.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Establece si se debe optimizar el PDF de salida para la navegación en línea con un navegador web.

Para un ejemplo de código, consulte esta [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linearize | boolean | true  para optimizar el PDF de salida para la navegación en línea,  false  de lo contrario. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Las anotaciones pueden eliminarse cuando son innecesarias. Cuando son necesarias pero no requieren edición adicional, pueden aplanarse. Esto reducirá el tamaño del archivo.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  si las anotaciones se eliminan,  false  de lo contrario.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Establece si se deben eliminar las anotaciones innecesarias del PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeAnnotations | boolean | true  para eliminar anotaciones innecesarias,  false  de lo contrario. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Si el documento PDF contiene AcroForms, podemos intentar reducir el tamaño del archivo aplanando los campos de formulario.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  si los campos de formulario se eliminan,  false  de lo contrario.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Establece si se deben eliminar los campos de formulario del PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeFormFields | boolean | true  para eliminar los campos de formulario,  false  de lo contrario. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


El archivo PDF está compuesto por Texto, Imagen, Adjuntos, Anotaciones, Gráficos y otros objetos. Puede encontrarse con la necesidad de convertir un PDF del espacio de color RGB a escala de grises para que la impresión de esos archivos PDF sea más rápida. Además, cuando el archivo se convierte a escala de grises, el tamaño del documento también se reduce, pero con este cambio, la calidad del documento puede disminuir. Actualmente, esta función está soportada por la función Pre-Flight de Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  si el PDF se convierte a escala de grises,  false  de lo contrario.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Establece si se debe convertir el PDF a escala de grises.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| convertToGrayScale | boolean | true  para convertir el PDF a escala de grises,  false  de lo contrario. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Cada fuente utilizada para mostrar texto en la página contiene un conjunto de glifos para los caracteres de la fuente. La especificación PDF admite el \"font subset\", es decir, una fuente con solo los glifos que se utilizan. Esto puede causar problemas cuando el texto debe actualizarse (ya que probablemente falten los glifos necesarios en la fuente), pero para un documento que no se planea modificar, esto permite reducir el tamaño.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  si se realiza subsetting de las fuentes,  false  de lo contrario.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Establece si se deben crear subconjuntos de las fuentes en el PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subsetFonts | boolean | true  para aplicar subsetting a las fuentes,  false  de lo contrario. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Si el archivo PDF de origen contiene imágenes, considere comprimir las imágenes y establecer su calidad. Para habilitar la compresión de imágenes, establezca esta opción en true. Todas las imágenes en un documento serán recomprimidas. La compresión se define mediante la propiedad ImageQuality, que es el valor de la calidad en porcentaje. 100 % es calidad sin cambios. Para disminuir la calidad de la imagen, establezca la propiedad ImageQuality a menos de 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  si las imágenes están comprimidas,  false  de lo contrario.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Establece si se deben comprimir las imágenes en el PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressImages | boolean | true  para comprimir las imágenes,  false  de lo contrario. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Si el archivo PDF de origen contiene imágenes, considere comprimir las imágenes y establecer su calidad. Para habilitar la compresión de imágenes, establezca la opción CompressImages en true. Todas las imágenes en un documento serán recomprimidas. La compresión se define mediante la propiedad ImageQuality, que es el valor de la calidad en porcentaje. 100 % es calidad sin cambios. Para disminuir la calidad de la imagen, establezca la opción CompressImages en true y la propiedad ImageQuality a menos de 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - la calidad de la imagen (valor entre 1 y 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Establece la calidad de imagen para comprimir las imágenes en el PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageQuality | int | la calidad de la imagen (valor entre 1 y 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Puede usarse con la opción CompressImages para redimensionar las imágenes con una resolución más baja. En este caso, debemos establecer CompressImage en true, ResizeImages en true y MaxResolution al valor apropiado.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  si las imágenes se redimensionan,  false  de lo contrario.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Establece si se deben redimensionar las imágenes en el PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeImages | boolean | true  para redimensionar las imágenes,  false  de lo contrario. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Puede usarse con la opción CompressImages para redimensionar las imágenes con una resolución más baja. En este caso, debemos establecer CompressImage en true, ResizeImages en true y MaxResolution al valor apropiado.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - la resolución máxima para las imágenes.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Establece la resolución máxima para redimensionar las imágenes en el PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxResolution | int | la resolución máxima para las imágenes. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimiza los bordes y fuentes de las hojas de cálculo de Excel para un tamaño de archivo de salida más pequeño.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  si las hojas de cálculo están optimizadas,  false  de lo contrario.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Establece si se deben optimizar las hojas de cálculo en el PDF.

Para un ejemplo de código, consulte esta [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  para optimizar las hojas de cálculo,  false  de lo contrario. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Elimina la información privada (información de pieza de página) si está configurado como verdadero.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si la información privada se elimina,  false  de lo contrario.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Establece si se debe eliminar la información privada del PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removePrivateInfo | boolean | true  para eliminar la información privada,  false  de lo contrario. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Si el documento usa fuentes incrustadas, significa que todos los datos de la fuente están incluidos en el documento. La ventaja es que el documento se puede visualizar independientemente de si la fuente está instalada en la máquina del usuario\u2019s o no. Pero incrustar fuentes hace que el documento sea más grande. El método unembed fonts elimina todas las fuentes incrustadas. Esto reduce el tamaño del documento, pero el documento puede volverse ilegible si la fuente correcta no está instalada.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si las fuentes incrustadas están unembedded,  false  de lo contrario.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Establece si se deben desincorporar las fuentes incrustadas en el PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unembedFonts | boolean | true  para unembed las fuentes incrustadas,  false  de lo contrario. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


A veces un documento contiene varios flujos de recursos idénticos (por ejemplo imágenes). Esto puede ocurrir, por ejemplo, cuando un documento se concatena consigo mismo. El documento de salida contiene dos copias independientes del mismo flujo de recursos. Analizamos todos los flujos de recursos y los comparamos. Si los flujos están duplicados se fusionan, es decir, solo queda una copia, las referencias se cambian adecuadamente y se eliminan las copias del objeto. A veces esto reduce el tamaño del documento.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si los flujos duplicados están vinculados,  false  en caso contrario.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Establece si se deben enlazar los flujos duplicados en el PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  para vincular flujos duplicados,  false  en caso contrario. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Si esta propiedad está configurada como verdadera, el contenido de la página se reutilizará al optimizar el documento para páginas idénticas.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si el contenido de la página se reutiliza,  false  en caso contrario.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Establece si se permite reutilizar el contenido de la página en el PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| allowReusePageContent | boolean | true  para permitir reutilizar el contenido de la página,  false  en caso contrario. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


A veces un documento contiene flujos de recursos no utilizados. Estos flujos no son \\u201cobjetos no utilizados\\u201d porque están referenciados desde el diccionario de recursos de una página\\u2019s. Esto puede ocurrir en casos donde una imagen se ha eliminado de la página pero no de los recursos de la página. Además, esta situación a menudo ocurre cuando se extraen páginas del documento y las páginas del documento tienen recursos \\u201ccomunes\\u201d, es decir, el mismo objeto Resources. El contenido de las páginas se analiza para determinar si un flujo de recursos se usa o no. Los flujos no utilizados se eliminan. A veces esto reduce el tamaño del documento.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si los flujos no utilizados se eliminan,  false  en caso contrario.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Establece si se deben eliminar los flujos sin usar del PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  para eliminar flujos no utilizados,  false  en caso contrario. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


A veces un documento PDF contiene objetos PDF que no están referenciados por ningún otro objeto en el documento. Esto puede ocurrir, por ejemplo, cuando se elimina una página del árbol de páginas del documento pero el propio objeto de la página no se elimina. Eliminar estos objetos no hace que el documento sea inválido, sino que lo reduce.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si los objetos no utilizados se eliminan,  false  en caso contrario.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Establece si se deben eliminar los objetos sin usar del PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  para eliminar objetos no utilizados,  false  en caso contrario. |

