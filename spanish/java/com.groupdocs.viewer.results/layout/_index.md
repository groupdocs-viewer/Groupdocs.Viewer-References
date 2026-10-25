---
title: "Layout"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa un diseño contenido en un dibujo CAD."
type: docs
weight: 17
url: /es/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Representa un diseño contenido en un dibujo CAD.


La interfaz Layout define el contrato para acceder y manipular un diseño dentro de un dibujo CAD
en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el nombre del diseño,
dimensiones y otras propiedades.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Recupera el nombre del diseño. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Establece el nombre del diseño. |
|
|  | [getWidth()](#getWidth--) | Recupera el ancho del diseño. |
|
|  | [setWidth(double width)](#setWidth-double-) | Establece el ancho del diseño. |
|
|  | [getHeight()](#getHeight--) | Recupera la altura del diseño. |
|
|  | [setHeight(double height)](#setHeight-double-) | Establece la altura del diseño. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Comprueba si este objeto es igual al objeto proporcionado. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Recupera el nombre del diseño.


**Returns:**
java.lang.String - el nombre del diseño.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Establece el nombre del diseño.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | nombre | java.lang.String | El nombre a establecer para el diseño. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Recupera el ancho del diseño.


**Returns:**
double - el ancho del diseño.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Establece el ancho del diseño.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | width | double | El ancho a establecer para el diseño. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Recupera la altura del diseño.


**Returns:**
double - la altura del diseño.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Establece la altura del diseño.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | altura | double | La altura a establecer para el diseño. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Comprueba si este objeto es igual al objeto proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | otro | java.lang.Object | El objeto a comparar. |
|

**Returns:**
boolean -  true  si los objetos son iguales,  false  de lo contrario.

