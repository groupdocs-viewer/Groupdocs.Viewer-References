---
title: "Position"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Define la posición de la marca de agua."
type: docs
weight: 43
url: /es/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Define la posición de la marca de agua.


El enum Position representa diferentes posiciones para una marca de agua en el componente GroupDocs.Viewer.
Proporciona un conjunto de posiciones predefinidas que pueden usarse para especificar la ubicación de una marca de agua
en un documento o imagen durante el proceso de renderizado.


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


## Campos

| Campo | Descripción |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | La posición diagonal. |
|
|  | [TOP_LEFT](#TOP-LEFT) | La posición superior izquierda. |
|
|  | [TOP_CENTER](#TOP-CENTER) | La posición superior central. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | La posición superior derecha. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | La posición inferior izquierda. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | La posición inferior central. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | La posición inferior derecha. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


La posición diagonal.
Esta posición representa una alineación o ubicación diagonal.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


La posición superior izquierda.
Esta posición representa la alineación o ubicación en la esquina superior izquierda.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


La posición superior central.
Esta posición representa la alineación o ubicación en el centro superior.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


La posición superior derecha.
Esta posición representa la alineación o ubicación en la esquina superior derecha.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


La posición inferior izquierda.
Esta posición representa la alineación o ubicación en la esquina inferior izquierda.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


La posición inferior central.
Esta posición representa la alineación o ubicación en el centro inferior.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


La posición inferior derecha.
Esta posición representa la alineación o ubicación en la esquina inferior derecha.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
