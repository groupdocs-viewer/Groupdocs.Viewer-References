---
title: "Watermark"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa una marca de agua de texto."
type: docs
weight: 37
url: /es/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Representa una marca de agua de texto. Para más detalles, consulte la [documentation][].

La clase Watermark representa una marca de agua de texto en el componente GroupDocs.Viewer. Se utiliza para definir y aplicar una marca de agua a la salida renderizada de los documentos.

Ejemplo de uso:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Inicializa una nueva instancia de la clase Watermark. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Devuelve el texto de la marca de agua. |
| [getColor()](#getColor--) | Devuelve el color de la marca de agua. |
| [getColorAsHex()](#getColorAsHex--) | Devuelve el color de la marca de agua en formato hexadecimal. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Establece el color de la marca de agua. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Establece el color de la marca de agua. |
| [getPosition()](#getPosition--) | Devuelve la posición de la marca de agua. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Establece la posición de la marca de agua. |
| [getSize()](#getSize--) | Devuelve el tamaño de la marca de agua. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Establece el tamaño de la marca de agua. |
| [getFontName()](#getFontName--) | Devuelve el nombre de la fuente utilizada para la marca de agua. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Establece el nombre de la fuente utilizada para la marca de agua. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Inicializa una nueva instancia de la clase Watermark.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | java.lang.String | El texto de la marca de agua. |

### getText() {#getText--}
```
public final String getText()
```


Devuelve el texto de la marca de agua. Este método recupera el texto de la marca de agua aplicada al documento.

**Returns:**
java.lang.String - el texto de la marca de agua.
### getColor() {#getColor--}
```
public final Color getColor()
```


Devuelve el color de la marca de agua. Este método recupera el color de la marca de agua aplicada al documento.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - el color de la marca de agua.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Devuelve el color de la marca de agua en formato hexadecimal. Este método recupera el color de la marca de agua aplicada al documento.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - el color de la marca de agua en formato hexadecimal.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Establece el color de la marca de agua. Este método establece el color de la marca de agua aplicada al documento.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.Color | El color de la marca de agua a establecer. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Establece el color de la marca de agua. Este método establece el color de la marca de agua aplicada al documento.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorName | java.lang.String | El color de la marca de agua a establecer. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Devuelve la posición de la marca de agua. Este método devuelve la posición de la marca de agua aplicada al documento.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Establece la posición de la marca de agua. Este método establece la posición de la marca de agua aplicada al documento.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | La posición de la marca de agua. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Devuelve el tamaño de la marca de agua. Este método recupera el tamaño de la marca de agua aplicada al documento.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Establece el tamaño de la marca de agua. Este método establece el tamaño de la marca de agua que se aplicará al documento.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | El tamaño de la marca de agua. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Devuelve el nombre de la fuente utilizada para la marca de agua.

**Returns:**
java.lang.String - el nombre de fuente utilizado para la marca de agua.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Establece el nombre de la fuente utilizada para la marca de agua.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | El nombre de fuente utilizado para la marca de agua. |

