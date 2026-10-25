---
title: "FontStyles"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt 4 mogelijke stijlen van het in het document gebruikte lettertype voor: Regular, Bold, Italic of Bold Italic."
type: docs
weight: 13
url: /nl/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Stelt 4 mogelijke stijlen van het lettertype voor, gebruikt in het document: Regular, Bold, Italic of Bold Italic.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Maakt een FontStyles‑instantie aan op basis van vet/italic‑vlaggen. |
|
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Converteert een stijlwaarde naar een menselijk leesbare tekenreeks. |
|
|  | [getName()](#getName--) | Retourneert de leesbare naam van deze lettertype‑stijl. |
|
|  | [isBold()](#isBold--) | Retourneert true als de vet-bit is ingesteld. |
|
|  | [isItalic()](#isItalic--) | Retourneert true als de cursief-bit is ingesteld. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Unie (C#-operator +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Verschil (C#-operator -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Parseert een lettertype‑stijlnamen naar FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Maakt een FontStyles‑instantie aan op basis van vet/italic‑vlaggen.


**Parameters:**
| Parameter | Type | Beschrijving |
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


Converteert een stijlwaarde naar een menselijk leesbare tekenreeks.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stijl | int | de lettertype‑stijelwaarde |
|

**Returns:**
java.lang.String - een stringrepresentatie van de lettertype‑stijl

### getName() {#getName--}
```
public String getName()
```


Retourneert de leesbare naam van deze lettertype‑stijl.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Retourneert true als de vet-bit is ingesteld.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Retourneert true als de cursief-bit is ingesteld.


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
| Parameter | Type | Beschrijving |
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


Unie (C#-operator +)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eerste | com.groupdocs.viewer.fonts.FontStyles |  |
| tweede | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Verschil (C#-operator -)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minuend | com.groupdocs.viewer.fonts.FontStyles |  |
| subtrahend | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Parseert een lettertype‑stijlnamen naar FontStyles.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stijl | java.lang.String |  |
| geparseerd | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true bij succes, false anders.

