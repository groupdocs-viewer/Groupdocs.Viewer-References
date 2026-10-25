---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Encapsula metadatos y datos binarios de una fuente sustituida utilizada en un documento de Procesamiento de texto a través de GroupDocs.Viewer."
type: docs
weight: 18
url: /es/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Encapsula metadatos y datos binarios de una fuente sustituida utilizada en un documento WordProcessing a través de GroupDocs.Viewer. Clase inmutable.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Constructor para inicializar todos los campos. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Devuelve el nombre de familia de la fuente sustituida (nunca nulo). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | Devuelve el nombre de familia de la fuente original (nunca nulo). |
|
|  | [getStyle()](#getStyle--) | Devuelve el estilo de la fuente original. |
|
|  | [getContent()](#getContent--) | Devuelve el contenido binario de la fuente sustituida (nunca nulo). |
|
|  | [getFormat()](#getFormat--) | Devuelve el formato de la fuente sustituida. |
|
|  | [toString()](#toString--) | Devuelve una cadena que describe esta fuente sustituida: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Igualdad basada en la familia original, la familia sustituida y el estilo. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializa esta fuente como una regla CSS @font-face usando un método de utilidad. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Constructor para inicializar todos los campos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | El nombre de la fuente original (no encontrado en el sistema) |
|
|  | substitutedFamilyName | java.lang.String | El nombre de la fuente sustituida (disponible) |
|
|  | estilo | com.groupdocs.viewer.fonts.FontStyles | Estilo de fuente (Regular, Bold, Italic, BoldItalic) |
|
|  | content | byte[] | Contenido binario de la fuente sustituida (nunca nulo) |
|
|  | formato | int | Formato de fuente (TrueType, OpenType, etc.) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Devuelve el nombre de familia de la fuente sustituida (nunca nulo).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Devuelve el nombre de familia de la fuente original (nunca nulo).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Devuelve el estilo de la fuente original.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Devuelve el contenido binario de la fuente sustituida (nunca nulo).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Devuelve el formato de la fuente sustituida.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que describe esta fuente sustituida: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Igualdad basada en la familia original, la familia sustituida y el estilo. Requerido para su uso en HashSet o HashMap como C# IEqualityComparer.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializa esta fuente como una regla CSS @font-face usando un método de utilidad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| output | java.io.Writer |  |

