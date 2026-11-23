---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Encapsula metadatos y datos binarios de una fuente utilizada en un documento Presentation cargado en la instancia Viewer."
type: docs
weight: 15
url: /es/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Encapsula metadatos y datos binarios de una fuente utilizada en un documento Presentation, cargado en la instancia Viewer. Esta fuente se usa en el contenido del documento y puede estar incrustada dentro del propio documento o instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtiene el nombre de familia de la fuente (nunca nulo o vacío). |
|
|  | [getStyle()](#getStyle--) | Obtiene el estilo de la fuente: Regular, Bold, Italic o BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indica si esta fuente está incrustada dentro del documento cargado en la instancia Viewer. |
|
|  | [getFormat()](#getFormat--) | Obtiene el formato de la fuente (TrueType, OpenType, etc.). |
|
|  | [getContent()](#getContent--) | Obtiene el contenido binario de la fuente, o null si los datos de la fuente no están disponibles. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa la información de esta fuente en una regla CSS @font-face usando el escritor especificado. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtiene el nombre de familia de la fuente (nunca nulo o vacío).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Obtiene el estilo de la fuente: Regular, Bold, Italic o BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indica si esta fuente está incrustada dentro del documento cargado en la instancia Viewer. Nota: Los documentos Spreadsheet no pueden contener fuentes incrustadas, por lo que para ellos siempre devuelve false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Obtiene el formato de la fuente (TrueType, OpenType, etc.). Si solo están disponibles los metadatos, devuelve FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtiene el contenido binario de la fuente, o null si los datos de la fuente no están disponibles.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializa la información de esta fuente en una regla CSS @font-face usando el escritor especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | output | java.io.Writer | escritor para escribir CSS (no debe ser null) |
|

