---
title: "Size"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Contiene el tamaño de la marca de agua."
type: docs
weight: 30
url: /es/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Contiene el tamaño de la marca de agua.


La clase Size representa el tamaño de una marca de agua en el componente GroupDocs.Viewer.
Proporciona opciones para especificar las dimensiones de la marca de agua, como ancho y alto.


Ejemplo de uso:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Inicializa una nueva instancia de la |
Size
clase.
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Representa el tamaño máximo del texto de marca de agua que cabe en la página. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Representa la mitad del tamaño máximo del texto de marca de agua que cabe en la página. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Representa un tercio del tamaño máximo del texto de marca de agua que cabe en la página. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Devuelve el tamaño del texto de marca de agua en porcentajes en relación con el ancho de la página. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Inicializa una nueva instancia de la
Size
clase.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | relativeSize | byte | El tamaño en porcentajes en relación con el tamaño de la página. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Representa el tamaño máximo del texto de marca de agua que cabe en la página.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Representa la mitad del tamaño máximo del texto de marca de agua que cabe en la página.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Representa un tercio del tamaño máximo del texto de marca de agua que cabe en la página.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Devuelve el tamaño del texto de marca de agua en porcentajes en relación con el ancho de la página.


**Returns:**
byte - el tamaño del texto de marca de agua en porcentajes.

