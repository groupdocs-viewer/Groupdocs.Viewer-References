---
title: "Resource"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa un recurso HTML como fuente, estilo, imagen o gráficos."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Representa un recurso HTML como fuente, estilo, imagen o gráficos.


La clase Resource representa un recurso utilizado en la renderización HTML en el componente GroupDocs.Viewer.
Puede representar varios tipos de recursos, como fuentes, estilos, imágenes o gráficos, que se incluyen
o se hacen referencia en la salida HTML generada durante el proceso de renderizado.


Ejemplo de uso:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Crea una nueva instancia de la |
Resource
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFileName()](#getFileName--) | Devuelve el nombre de archivo del recurso. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | Establece el nombre de archivo del recurso. |
|
|  | [isNested()](#isNested--) | Devuelve si el recurso se encuentra dentro de otro recurso, p. ej. un recurso de fuente que se encuentra en un recurso CSS o SVG. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | Establece si el recurso se encuentra dentro de otro recurso. |
|
|  | [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Crea una nueva instancia de la
Resource
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileName | java.lang.String | El nombre de archivo del recurso. |
|
|  | anidado | boolean | Indica si el recurso se encuentra dentro de otro recurso, p. ej., un recurso de fuente que se encuentra en un recurso CSS o SVG. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Devuelve el nombre de archivo del recurso.


**Returns:**
java.lang.String - el nombre de archivo del recurso.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Establece el nombre de archivo del recurso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileName | java.lang.String | El nuevo nombre de archivo para el recurso. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


Devuelve si el recurso se encuentra dentro de otro recurso, p. ej. un recurso de fuente que se encuentra en un recurso CSS o SVG.


**Returns:**
boolean - Si el recurso reside dentro de otro recurso.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Establece si el recurso se encuentra dentro de otro recurso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | anidado | boolean | Si el recurso debe establecerse como anidado. |
|

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.


**Returns:**
java.lang.String - la representación en cadena del objeto actual.

