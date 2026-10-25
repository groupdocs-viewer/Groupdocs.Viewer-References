---
title: "FontStyles"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar 4 möjliga stilar för teckensnittet som används i dokumentet Regular, Bold, Italic eller Bold Italic."
type: docs
weight: 13
url: /sv/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Representerar 4 möjliga stilar för teckensnittet som används i dokumentet: Regular, Bold, Italic eller Bold Italic.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Skapar en FontStyles-instans från fet/kursiv-flaggor. |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Konverterar ett stilvärde till en människoläsbar sträng. |
|
|  | [getName()](#getName--) | Returnerar ett läsbart namn för denna teckensnittsstil. |
|
|  | [isBold()](#isBold--) | Returnerar true om fet-bit är satt. |
|
|  | [isItalic()](#isItalic--) | Returnerar true om kursiv-bit är satt. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Union (C#-operator +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Differens (C#-operator -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Tolkar ett teckensnittsstilsnamn till FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Skapar en FontStyles-instans från fet/kursiv-flaggor.


**Parameters:**
| Parameter | Typ | Beskrivning |
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


Konverterar ett stilvärde till en människoläsbar sträng.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stil | int | teckensnittsstilvärdet |
|

**Returns:**
java.lang.String - en strängrepresentation av teckensnittsstilen

### getName() {#getName--}
```
public String getName()
```


Returnerar ett läsbart namn för denna teckensnittsstil.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Returnerar true om fet-bit är satt.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Returnerar true om kursiv-bit är satt.


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
| Parameter | Typ | Beskrivning |
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


Union (C#-operator +)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| första | com.groupdocs.viewer.fonts.FontStyles |  |
| andra | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Differens (C#-operator -)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minuend | com.groupdocs.viewer.fonts.FontStyles |  |
| subtrahend | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Tolkar ett teckensnittsstilsnamn till FontStyles.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stil | java.lang.String |  |
| parsad | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true vid framgång, false annars.

