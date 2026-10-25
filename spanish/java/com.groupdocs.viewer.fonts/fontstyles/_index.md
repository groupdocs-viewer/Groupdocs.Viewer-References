---
title: "FontStyles"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa 4 estilos posibles de la fuente utilizada en el documento: Regular, Bold, Italic o Bold Italic."
type: docs
weight: 13
url: /es/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Representa 4 estilos posibles de la fuente, usados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Crea una instancia de FontStyles a partir de los indicadores bold/italic. |
|
## Campos

| Campo | Descripción |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Convierte un valor de estilo a una cadena legible por humanos. |
|
|  | [getName()](#getName--) | Devuelve el nombre legible de este estilo de fuente. |
|
|  | [isBold()](#isBold--) | Devuelve true si el bit de negrita está activado. |
|
|  | [isItalic()](#isItalic--) | Devuelve true si el bit de cursiva está activado. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Unión (operador C# +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Diferencia (operador C# -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Analiza un nombre de estilo de fuente a FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Crea una instancia de FontStyles a partir de los indicadores bold/italic.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


Convierte un valor de estilo a una cadena legible por humanos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | estilo | int | el valor del estilo de fuente |
|

**Returns:**
java.lang.String - una representación en cadena del estilo de fuente

### getName() {#getName--}
```
public String getName()
```


Devuelve el nombre legible de este estilo de fuente.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Devuelve true si el bit de negrita está activado.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Devuelve true si el bit de cursiva está activado.


**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


Unión (operador C# +)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| primero | com.groupdocs.viewer.fonts.FontStyles |  |
| segundo | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Diferencia (operador C# -)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minuendo | com.groupdocs.viewer.fonts.FontStyles |  |
| sustraendo | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Analiza un nombre de estilo de fuente a FontStyles.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| estilo | java.lang.String |  |
| analizado | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true en caso de éxito, false en caso contrario.

