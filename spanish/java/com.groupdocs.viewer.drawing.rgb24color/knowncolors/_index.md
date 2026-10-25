---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: 
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Métodos

| Método | Descripción |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Intenta encontrar un color por su nombre en forma de cadena. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Intenta encontrar el nombre de un color a partir de su valor RGB. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Intenta encontrar un color por su nombre en forma de cadena.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | palabra clave | java.lang.String | Un nombre de color. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | El contenedor de resultados para el color encontrado, o CssLevel1.Black en caso de fallo. |
|

**Returns:**
booleano - Verdadero si el color se encontró correctamente por nombre, falso en caso contrario.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Intenta encontrar el nombre de un color a partir de su valor RGB.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Una instancia de color. |
|
|  | nombre | java.lang.String[] | El contenedor de resultados para el nombre de color encontrado, o null en caso de fallo. |
|

**Returns:**
booleano - Verdadero si el nombre se encontró correctamente para el color dado, falso en caso contrario.

