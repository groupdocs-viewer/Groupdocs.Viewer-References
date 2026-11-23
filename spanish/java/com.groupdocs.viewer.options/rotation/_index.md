---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Contiene la rotación de la página en grados en sentido horario."
type: docs
weight: 45
url: /es/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Contiene la rotación de la página en grados (en sentido horario).


El enum Rotation representa diferentes ángulos de rotación para una página en el componente GroupDocs.Viewer.
Proporciona un conjunto de opciones de rotación predefinidas que pueden usarse para especificar el ángulo de rotación
para renderizar una página en varios escenarios de visualización o conversión de documentos.


Ejemplo de uso:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | La rotación de página de 90 grados. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | La rotación de página de 180 grados. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | La rotación de página de 270 grados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


La rotación de página de 90 grados.
Esta rotación representa una rotación de 90 grados en sentido horario de la página.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


La rotación de página de 180 grados.
Esta rotación representa una rotación de 180 grados en sentido horario de la página.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


La rotación de página de 270 grados.
Esta rotación representa una rotación de 270 grados en sentido horario de la página.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
