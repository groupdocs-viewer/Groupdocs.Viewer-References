---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Encapsula metainformación y datos binarios de una fuente del documento de hoja de cálculo cargado en la instancia del Viewer."
type: docs
weight: 16
url: /es/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Encapsula metainformación y datos binarios de una fuente del documento de hoja de cálculo, cargado en la instancia del Viewer. Los documentos de hoja de cálculo no pueden tener fuentes incrustadas, por lo que esta fuente en particular, si es devuelta por el método Viewer.getAllFonts(), está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Nombre de familia de la fuente, sin estilo, nunca nulo o vacío. |
|
|  | [getStyle()](#getStyle--) | Estilo de esta fuente \u2014 puede ser Regular, Bold, Italic o BoldItalic. |
|
|  | [isStrikeout()](#isStrikeout--) | Indica si la fuente tiene un tachado simple. |
|
|  | [isUnderline()](#isUnderline--) | Indica si la fuente tiene subrayado. |
|
|  | [getColor()](#getColor--) | Color de esta fuente. |
|
|  | [getCharset()](#getCharset--) | Conjunto de caracteres de esta fuente. |
|
|  | [getContent()](#getContent--) | Contenido de esta fuente como una matriz de bytes. |
|
|  | [getFormat()](#getFormat--) | Formato de esta fuente. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa la información de esta fuente como una regla @font-face y la escribe en el escritor especificado. |
|
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


Estilo de esta fuente \u2014 puede ser Regular, Bold, Italic o BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indica si la fuente tiene un tachado simple.


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
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
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


Serializa la información de esta fuente como una regla @font-face y la escribe en el escritor especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | output | java.io.Writer | Dispositivo en el que escribir los datos de texto serializados. |
|

