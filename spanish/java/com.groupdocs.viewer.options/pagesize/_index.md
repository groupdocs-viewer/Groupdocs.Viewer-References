---
title: "PageSize"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "El tamaño de la página."
type: docs
weight: 42
url: /es/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

El tamaño de la página.


El enum PageSize representa diferentes tamaños de página en el componente GroupDocs.Viewer.
Proporciona un conjunto de tamaños de página predefinidos que pueden usarse para especificar las dimensiones
de una página en varios escenarios de renderizado de documentos.


Ejemplo de uso:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | El tamaño de página predeterminado, no especificado. |
|
|  | [LETTER](#LETTER) | El tamaño de la página Letter en puntos es 792 x 612. |
|
|  | [LEDGER](#LEDGER) | El tamaño de la página A0 en puntos es 3371 x 2384. |
|
|  | [A0](#A0) | El tamaño de la página A1 en puntos es 2384 x 1685. |
|
|  | [A1](#A1) | El tamaño de la página A2 en puntos es 1684 x 1190. |
|
|  | [A2](#A2) | El tamaño de la página A3 en puntos es 1190 x 842. |
|
|  | [A3](#A3) | El tamaño de la página A3 en puntos es 1190 x 842. |
|
|  | [A4](#A4) | El tamaño de la página A4 en puntos es 842 x 595. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


El tamaño de página predeterminado, no especificado.
Este tamaño se usa cuando no se especifica un tamaño de página específico.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


El tamaño de la página Letter en puntos es 792 x 612.
Este tamaño de página se usa comúnmente para cartas y documentos en Norteamérica.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


El tamaño de la página A0 en puntos es 3371 x 2384.
Este tamaño de página grande forma parte de la norma internacional ISO 216.


### A0 {#A0}
```
public static final PageSize A0
```


El tamaño de la página A1 en puntos es 2384 x 1685.
Este tamaño de página forma parte de la norma internacional ISO 216.


### A1 {#A1}
```
public static final PageSize A1
```


El tamaño de la página A2 en puntos es 1684 x 1190.
Este tamaño de página forma parte de la norma internacional ISO 216.


### A2 {#A2}
```
public static final PageSize A2
```


El tamaño de la página A3 en puntos es 1190 x 842.
Este tamaño de página forma parte de la norma internacional ISO 216.


### A3 {#A3}
```
public static final PageSize A3
```


El tamaño de la página A3 en puntos es 1190 x 842.
Este tamaño de página forma parte de la norma internacional ISO 216.


### A4 {#A4}
```
public static final PageSize A4
```


El tamaño de la página A4 en puntos es 842 x 595.
Este tamaño de página forma parte de la norma internacional ISO 216.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
