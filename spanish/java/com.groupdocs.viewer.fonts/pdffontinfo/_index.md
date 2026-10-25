---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Encapsula la metainformación y los datos binarios de una fuente de un documento PDF cargado en la instancia del Viewer."
type: docs
weight: 14
url: /es/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Encapsula meta‑información y datos binarios de una fuente de un documento PDF, cargada en la instancia del Viewer.


Esta fuente se usa en el contenido del documento y es una de las siguientes:

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Constructor interno usado por la extracción de fuentes PDF. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtiene el nombre de la familia de la fuente. |
|
|  | [getStyle()](#getStyle--) | Obtiene el estilo de esta fuente. |
|
|  | [isEmbedded()](#isEmbedded--) | Devuelve si la fuente está incrustada dentro del documento PDF. |
|
|  | [isInstalled()](#isInstalled--) | Devuelve si la fuente está instalada en el SO. |
|
|  | [getFormat()](#getFormat--) | Devuelve el formato de archivo de la fuente. |
|
|  | [getContent()](#getContent--) | Devuelve el contenido binario de la fuente. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa esta fuente como una regla CSS @font-face. |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Constructor interno usado por la extracción de fuentes PDF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | familyName | java.lang.String | nombre de la familia de fuentes |
|
|  | estilo | com.groupdocs.viewer.fonts.FontStyles | estilo (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | true si la fuente está incrustada en el PDF |
|
|  | isInstalled | boolean | true si la fuente está instalada en el SO |
|
|  | content | byte[] | datos binarios de la fuente (nullable) |
|
|  | formato | int | formato de archivo de fuente |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtiene el nombre de la familia de la fuente.


**Returns:**
java.lang.String - cadena de nombre de familia (nunca nula o vacía)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Obtiene el estilo de esta fuente.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - el estilo de la fuente

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Devuelve si la fuente está incrustada dentro del documento PDF.


**Returns:**
boolean - true si está incrustada

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Devuelve si la fuente está instalada en el SO.


**Returns:**
boolean - true si está instalada

### getFormat() {#getFormat--}
```
public int getFormat()
```


Devuelve el formato de archivo de la fuente.


**Returns:**
int - el enum del formato de fuente

### getContent() {#getContent--}
```
public byte[] getContent()
```


Devuelve el contenido binario de la fuente.


**Returns:**
byte[] - matriz de bytes o null si no está disponible

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializa esta fuente como una regla CSS @font-face.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | output | java.io.Writer | escritor al que se escribirá el CSS |
|

