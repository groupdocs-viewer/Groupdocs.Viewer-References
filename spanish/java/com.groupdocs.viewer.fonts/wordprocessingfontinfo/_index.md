---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Encapsula metainformación y datos binarios de una fuente del documento WordProcessing cargado en la instancia Viewer."
type: docs
weight: 17
url: /es/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Encapsula metainformación y datos binarios de una fuente del documento WordProcessing, cargado en la instancia Viewer. Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.

Clase inmutable. Sus instancias son producidas y devueltas por GroupDocs.Viewer
API pública y normalmente no debería ser creada por el usuario.
Para obtener más detalles, consulte la documentación:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Nombre de familia de la fuente, sin estilo, nunca nulo o vacío. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Nombre de familia alternativo de la fuente. |
|
|  | [getStyle()](#getStyle--) | Estilo de la fuente \u2014 puede ser Regular, Bold, Italic o BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indica si esta fuente está incrustada dentro del documento (true) o es una fuente del sistema (false). |
|
|  | [getFormat()](#getFormat--) | Formato de esta fuente. |
|
|  | [getContent()](#getContent--) | Contenido de esta fuente como una matriz de bytes, o null si no está disponible. |
|
|  | [getCharset()](#getCharset--) | Conjunto de caracteres de esta fuente. |
|
|  | [toString()](#toString--) | Devuelve información de depuración sobre esta fuente en la siguiente plantilla: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa la información de esta fuente como una regla CSS @font-face y la escribe en el escritor especificado. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nombre de familia de la fuente, sin estilo, nunca nulo o vacío.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Nombre de familia alternativo de la fuente. Si falta, devuelve una cadena vacía.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Estilo de la fuente \u2014 puede ser Regular, Bold, Italic o BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indica si esta fuente está incrustada dentro del documento (true) o es una fuente del sistema (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formato de esta fuente. Si solo hay metainformación y falta el contenido binario, puede devolver FontFormat.UNKNOWN.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenido de esta fuente como una matriz de bytes, o null si no está disponible.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Conjunto de caracteres de esta fuente.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Devuelve información de depuración sobre esta fuente en la siguiente plantilla: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializa la información de esta fuente como una regla CSS @font-face y la escribe en el escritor especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | output | java.io.Writer | Escritor que recibirá el CSS serializado. |
|

