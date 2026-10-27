---
title: "TextOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Opciones de división de archivos de texto en páginas."
type: docs
weight: 32
url: /es/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Opciones de división de archivos de texto en páginas.

La clase TextOptions proporciona opciones para dividir archivos de texto en páginas en el componente GroupDocs.Viewer. Permite controlar cómo se dividen los archivos de texto en páginas individuales para su renderizado y visualización.

Ejemplo de uso:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextOptions()](#TextOptions--) | Inicializa una nueva instancia de la clase TextOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Obtiene el número máximo de caracteres por fila en una página. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Establece el número máximo de caracteres por fila en una página. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Obtiene el número máximo de filas por página. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Establece el número máximo de filas por página. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Inicializa una nueva instancia de la clase TextOptions.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Obtiene el número máximo de caracteres por fila en una página.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - el número máximo de caracteres por fila en una página.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Establece el número máximo de caracteres por fila en una página.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxCharsPerRow | int | El número máximo de caracteres por fila en una página. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Obtiene el número máximo de filas por página.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - el número máximo de filas.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Establece el número máximo de filas por página.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxRowsPerPage | int | El número máximo de filas. |

