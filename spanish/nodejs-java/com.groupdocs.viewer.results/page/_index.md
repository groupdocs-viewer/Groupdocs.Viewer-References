---
title: "Página"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa una sola página que puede visualizarse."
type: docs
weight: 21
url: /es/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Representa una sola página que puede visualizarse.

La interfaz Page define el contrato para acceder y manipular una sola página que puede verse en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el número de página, el tamaño y otras propiedades.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Recupera el nombre de la hoja de cálculo o página. |
| [setName(String name)](#setName-java.lang.String-) | Establece el nombre de la hoja de cálculo o página. |
| [getNumber()](#getNumber--) | Recupera el número de página. |
| [setNumber(int number)](#setNumber-int-) | Establece el número de página. |
| [isVisible()](#isVisible--) | Recupera el indicador de visibilidad de la página. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Establece el indicador de visibilidad de la página. |
| [getWidth()](#getWidth--) | Recupera el ancho de la página en píxeles al visualizarla como JPG o PNG. |
| [setWidth(int width)](#setWidth-int-) | Establece el ancho de la página en píxeles al visualizarla como JPG o PNG. |
| [getHeight()](#getHeight--) | Recupera la altura de la página en píxeles al visualizarla como JPG o PNG. |
| [setHeight(int height)](#setHeight-int-) | Establece la altura de la página en píxeles al visualizarla como JPG o PNG. |
| [getLines()](#getLines--) | Recupera las líneas contenidas en la página al visualizarla como JPG o PNG con extracción de texto habilitada. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Establece las líneas contenidas en la página al visualizarla como JPG o PNG con extracción de texto habilitada. |
### getName() {#getName--}
```
public abstract String getName()
```


Recupera el nombre de la hoja de cálculo o página.

**Returns:**
java.lang.String - el nombre de la hoja de cálculo o página.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Establece el nombre de la hoja de cálculo o página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | el nombre a establecer para la hoja de cálculo o página. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Recupera el número de página.

**Returns:**
int - el número de página.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Establece el número de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| número | int | el número de página a establecer. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Recupera el indicador de visibilidad de la página.

**Returns:**
boolean - el indicador de visibilidad de la página.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Establece el indicador de visibilidad de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| visible | boolean | true si la página es visible, false en caso contrario. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Recupera el ancho de la página en píxeles al visualizarla como JPG o PNG.

**Returns:**
int - el ancho de la página.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Establece el ancho de la página en píxeles al visualizarla como JPG o PNG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | el ancho a establecer para la página. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Recupera la altura de la página en píxeles al visualizarla como JPG o PNG.

**Returns:**
int - la altura de la página.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Establece la altura de la página en píxeles al visualizarla como JPG o PNG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| height | int | la altura a establecer para la página. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Recupera las líneas contenidas en la página al visualizarla como JPG o PNG con extracción de texto habilitada.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - las líneas contenidas en la página.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Establece las líneas contenidas en la página al visualizarla como JPG o PNG con extracción de texto habilitada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| líneas | java.util.List<com.groupdocs.viewer.results.Line> | la lista de líneas a establecer para la página. |

