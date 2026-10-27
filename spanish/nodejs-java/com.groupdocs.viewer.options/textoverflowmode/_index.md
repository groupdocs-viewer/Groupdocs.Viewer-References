---
title: "TextOverflowMode"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Define el modo de desbordamiento de texto para renderizar documentos de hojas de cálculo en HTML."
type: docs
weight: 46
url: /es/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Define el modo de desbordamiento de texto para renderizar documentos de hojas de cálculo en HTML.

El enum TextOverflowMode representa diferentes modos para manejar el desbordamiento de texto en el componente GroupDocs.Viewer. Proporciona un conjunto de opciones predefinidas que pueden usarse para controlar cómo se muestra el texto cuando supera el espacio disponible en las celdas durante la renderización de documentos de hoja de cálculo a HTML. Para más detalles, consulte la [documentation][].

Ejemplo de uso:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## Fields

| Field | Descripción |
| --- | --- |
| [OVERLAY](#OVERLAY) | Superponer celdas siguientes incluso si no están vacías. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Superponer celdas siguientes solo si están vacías. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Expandir columnas para ajustarse al texto. |
| [HIDE_TEXT](#HIDE-TEXT) | Ocultar el texto desbordado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Superponer celdas siguientes incluso si no están vacías. Este modo permite que el texto desborde a las celdas adyacentes, sin importar su contenido.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Superponer celdas siguientes solo si están vacías. Este modo permite que el texto desborde a las celdas adyacentes solo si esas celdas están vacías.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Expandir columnas para ajustarse al texto. Este modo ajusta automáticamente el ancho de las columnas para acomodar el texto desbordado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Ocultar el texto desbordado. Este modo oculta el texto desbordado, evitando que se muestre.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
