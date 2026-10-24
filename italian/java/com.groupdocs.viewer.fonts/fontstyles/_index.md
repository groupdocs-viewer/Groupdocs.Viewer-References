---
title: "FontStyles"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta 4 possibili stili del carattere usati nel documento: Regular, Bold, Italic o Bold Italic."
type: docs
weight: 13
url: /it/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Rappresenta 4 possibili stili del font, usati nel documento: Regular, Bold, Italic o Bold Italic.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Crea un'istanza FontStyles a partire dai flag bold/italic. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Converte un valore di stile in una stringa leggibile dall'uomo. |
|
|  | [getName()](#getName--) | Restituisce il nome leggibile di questo stile di carattere. |
|
|  | [isBold()](#isBold--) | Restituisce true se il bit grassetto è impostato. |
|
|  | [isItalic()](#isItalic--) | Restituisce true se il bit corsivo è impostato. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Unione (operatore C# +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Differenza (operatore C# -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Analizza un nome di stile di carattere in FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Crea un'istanza FontStyles a partire dai flag bold/italic.


**Parameters:**
| Parametro | Tipo | Descrizione |
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


Converte un valore di stile in una stringa leggibile dall'uomo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stile | int | il valore dello stile di carattere |
|

**Returns:**
java.lang.String - una rappresentazione stringa dello stile di carattere

### getName() {#getName--}
```
public String getName()
```


Restituisce il nome leggibile di questo stile di carattere.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Restituisce true se il bit grassetto è impostato.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Restituisce true se il bit corsivo è impostato.


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
| Parametro | Tipo | Descrizione |
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


Unione (operatore C# +)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| primo | com.groupdocs.viewer.fonts.FontStyles |  |
| secondo | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Differenza (operatore C# -)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minuendo | com.groupdocs.viewer.fonts.FontStyles |  |
| sottraendo | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Analizza un nome di stile di carattere in FontStyles.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stile | java.lang.String |  |
| analizzato | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true in caso di successo, false altrimenti.

