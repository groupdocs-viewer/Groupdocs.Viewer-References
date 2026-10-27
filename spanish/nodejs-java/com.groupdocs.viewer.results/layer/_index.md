---
title: "Layer"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa una capa contenida en un dibujo CAD."
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Representa una capa contenida en un dibujo CAD.

La interfaz Layer define el contrato para acceder y manipular una capa dentro de un dibujo CAD en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el nombre de la capa, la visibilidad y otras propiedades.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Obtiene el nombre de la capa. |
| [setName(String name)](#setName-java.lang.String-) | Establece el nombre de la capa. |
| [isVisible()](#isVisible--) | Comprueba la visibilidad de la capa. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Establece la visibilidad de la capa. |
| [equals(Object other)](#equals-java.lang.Object-) | Comprueba si este objeto es igual al objeto proporcionado. |
### getName() {#getName--}
```
public abstract String getName()
```


Obtiene el nombre de la capa.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - el nombre de la capa.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Establece el nombre de la capa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String | El nuevo nombre de la capa. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Comprueba la visibilidad de la capa.

Las capas de dibujo CAD que están desactivadas o congeladas son invisibles. Para renderizar capas que son invisibles, use la opción [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-).

**Returns:**
boolean -  true  si la capa es visible,  false  en caso contrario.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Establece la visibilidad de la capa.

Si  true , la capa será visible; si  false , estará oculta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | Si la capa debe ser visible o no. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Comprueba si este objeto es igual al objeto proporcionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | java.lang.Object | El objeto a comparar. |

**Returns:**
boolean -  true  si los objetos son iguales,  false  de lo contrario.
