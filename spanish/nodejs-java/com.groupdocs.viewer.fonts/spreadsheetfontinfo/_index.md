---
title: "SpreadsheetFontInfo"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Encapsula metainformación y datos binarios de una fuente del documento Spreadsheet cargado en la instancia Viewer."
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Encapsula metainformación y datos binarios de una fuente del documento Spreadsheet, cargado en la instancia Viewer. Los documentos Spreadsheet no pueden contener fuentes incrustadas, por lo que esta fuente en particular, si es devuelta por el método Viewer.getAllFonts(), está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nombre de familia de la fuente, sin estilo, nunca nulo o vacío. |
| [getStyle()](#getStyle--) | Estilo de esta fuente — puede ser Regular, Bold, Italic o BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Indica si la fuente tiene un solo tachado. |
| [isUnderline()](#isUnderline--) | Indica si la fuente tiene subrayado. |
| [getColor()](#getColor--) | Color de esta fuente. |
| [getCharset()](#getCharset--) | Conjunto de caracteres de esta fuente. |
| [getContent()](#getContent--) | Contenido de esta fuente como una matriz de bytes. |
| [getFormat()](#getFormat--) | Formato de esta fuente. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor especificado. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nombre de familia de la fuente, sin estilo, nunca nulo o vacío.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Estilo de esta fuente — puede ser Regular, Bold, Italic o BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indica si la fuente tiene un solo tachado.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indica si la fuente tiene subrayado.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Color de esta fuente.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Conjunto de caracteres de esta fuente.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenido de esta fuente como una matriz de bytes. Puede ser nulo si solo está disponible la metainformación.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formato de esta fuente.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializa esta información de fuente como una regla @font-face y la escribe en el escritor especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| salida | java.io.Writer | Dispositivo donde escribir datos de texto serializados. |

