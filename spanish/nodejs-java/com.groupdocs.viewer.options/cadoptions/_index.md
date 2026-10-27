---
title: "CadOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar dibujos CAD."
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Proporciona opciones para renderizar dibujos CAD.

La clase CadOptions encapsula varios ajustes y parámetros que pueden usarse para controlar la renderización de dibujos CAD en el componente GroupDocs.Viewer.

Para obtener más información y ejemplos de código, consulte el [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] y el [Specify rendering options for CAD files][].

Ejemplo de uso:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Fields

| Field | Descripción |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPc3File()](#getPc3File--) | Obtiene el archivo PC3 (Configuración del Plotter) asociado al plotter. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Establece el archivo PC3 (Configuración del Plotter) asociado al plotter. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Inicializa una nueva instancia de la clase  CadOptions  para renderizar por factor de escala. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Inicializa una nueva instancia de la clase  CadOptions  para renderizar por ancho. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Inicializa una nueva instancia de la clase  CadOptions  para renderizar por altura. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Inicializa una nueva instancia de la clase CadOptions para renderizar por ancho y alto. |
| [getScaleFactor()](#getScaleFactor--) | Obtiene el factor de escala para el renderizado. |
| [getWidth()](#getWidth--) | Obtiene el ancho del resultado de salida en píxeles. |
| [getHeight()](#getHeight--) | Obtiene la altura del resultado de salida en píxeles. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo de la imagen. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Obtiene el color de fondo de la imagen. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Establece el color de fondo de la imagen. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Establece el color de fondo de la imagen. |
| [getTiles()](#getTiles--) | Obtiene las regiones de dibujo a renderizar. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Establece las regiones de dibujo a renderizar. |
| [isRenderLayouts()](#isRenderLayouts--) | Indica si los diseños del documento CAD deben renderizarse. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Establece si los diseños del documento CAD deben renderizarse. |
| [getLayoutName()](#getLayoutName--) | Obtiene el nombre del diseño específico a renderizar. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Establece el nombre del diseño específico a renderizar. |
| [getLayers()](#getLayers--) | Obtiene las capas de dibujo CAD a renderizar. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Obtiene las capas de dibujo CAD a renderizar. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Establecer este indicador en true habilita un modo de conversión especial orientado al rendimiento para todos los formatos dentro de la familia CAD. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Establecer este indicador en true habilita un modo de conversión especial orientado al rendimiento para todos los formatos dentro de la familia CAD. |
| [equals(Object o)](#equals-java.lang.Object-) | Comprueba si este objeto CadOptions es igual a otro objeto. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Obtiene el archivo PC3 (Configuración del Plotter) asociado al plotter.

**Returns:**
java.lang.String - la ruta del archivo PC3.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Establece el archivo PC3 (Configuración del Plotter) asociado al plotter.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pc3File | java.lang.String | La ruta del archivo PC3. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Inicializa una nueva instancia de la clase  CadOptions  para renderizar por factor de escala.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleFactor | double | El factor de escala para el renderizado. Los valores mayores que 1 ampliarán el resultado de salida, mientras que los valores entre 0 y 1 harán que el resultado de salida sea más pequeño. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Inicializa una nueva instancia de la clase  CadOptions  para renderizar por ancho.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho del resultado de salida en píxeles. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Inicializa una nueva instancia de la clase  CadOptions  para renderizar por altura.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| height | int | La altura del resultado de salida en píxeles. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Inicializa una nueva instancia de la clase CadOptions para renderizar por ancho y alto.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho del resultado de salida en píxeles. |
| height | int | La altura del resultado de salida en píxeles. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Obtiene el factor de escala para el renderizado. Los valores superiores a 1 ampliarán el resultado de salida, mientras que los valores entre 0 y 1 harán que el resultado de salida sea más pequeño.

**Returns:**
double - el factor de escala para el renderizado.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho del resultado de salida en píxeles.

**Returns:**
int - el ancho del resultado de salida.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura del resultado de salida en píxeles.

**Returns:**
int - la altura del resultado de salida.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene el color de fondo de la imagen.

**Returns:**
java.awt.Color - el color de fondo de la imagen.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Obtiene el color de fondo de la imagen.

**Returns:**
java.lang.String - el color de fondo de la imagen en formato 0xFFFFFF.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Establece el color de fondo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| backgroundColor | java.awt.Color | El color de fondo de la imagen. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Establece el color de fondo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorName | java.lang.String | El nombre del color de fondo de la imagen. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Obtiene las regiones de dibujo a renderizar.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - la lista de regiones de dibujo a renderizar.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Establece las regiones de dibujo a renderizar.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | La lista de regiones de dibujo a renderizar. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Indica si los diseños del documento CAD deben renderizarse.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  si los diseños deben renderizarse,  false  de lo contrario.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Establece si los diseños del documento CAD deben renderizarse.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para renderizar diseños,  false  de lo contrario. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Obtiene el nombre del diseño específico a renderizar. El nombre del diseño distingue entre mayúsculas y minúsculas.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - el nombre del diseño específico a renderizar.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Establece el nombre del diseño específico a renderizar. El nombre del diseño distingue entre mayúsculas y minúsculas.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | El nombre del diseño específico a renderizar. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Obtiene las capas de dibujo CAD a renderizar.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - las capas de dibujo CAD.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Obtiene las capas de dibujo CAD a renderizar.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | Las capas de dibujo CAD. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Establecer esta bandera a true habilita un modo de conversión especial orientado al rendimiento para todos los formatos dentro de la familia CAD. En este modo, la velocidad de conversión es mucho más rápida, pero la calidad de los documentos resultantes es significativamente peor. Por defecto, está desactivada (false). La calidad de los documentos resultantes es la mejor posible a costa del rendimiento.

**Returns:**
boolean -  true  si el modo de conversión orientado al rendimiento está habilitado,  false  de lo contrario.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Establecer esta bandera a true habilita un modo de conversión especial orientado al rendimiento para todos los formatos dentro de la familia CAD. En este modo, la velocidad de conversión es mucho más rápida, pero la calidad de los documentos resultantes es significativamente peor. Por defecto, está desactivada (false). La calidad de los documentos resultantes es la mejor posible a costa del rendimiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  para habilitar el modo de conversión orientado al rendimiento,  false  para desactivarlo. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Comprueba si este objeto CadOptions es igual a otro objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| o | java.lang.Object | El objeto con el que comparar. |

**Returns:**
boolean -  true  si los objetos son iguales,  false  de lo contrario.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcula el valor del código hash para este objeto. El código hash se basa en el estado interno del objeto y se utiliza en estructuras de datos basadas en hash, como mapas hash y conjuntos hash.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - el valor del código hash para este objeto.
### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en forma de cadena de este objeto.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - una representación en forma de cadena de este objeto.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Devuelve una representación en forma de cadena de este objeto.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| estilo | org.apache.commons.lang3.builder.ToStringStyle | El ToStringStyle a usar para generar la representación en forma de cadena. |

**Returns:**
java.lang.String - una representación en forma de cadena de este objeto usando el ToStringStyle especificado.
