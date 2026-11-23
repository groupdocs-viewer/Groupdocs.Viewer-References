---
title: "FontStyles"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt 4 mögliche Stile der im Dokument verwendeten Schriftart dar: Regular, Bold, Italic oder Bold Italic."
type: docs
weight: 13
url: /de/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Stellt 4 mögliche Schriftstile dar, die im Dokument verwendet werden: Normal, Fett, Kursiv oder Fett Kursiv.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Erstellt eine FontStyles‑Instanz aus Bold/Italic‑Flags. |
|
## Felder

| Feld | Beschreibung |
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

| Methode | Beschreibung |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Konvertiert einen Stilwert in eine menschenlesbare Zeichenkette. |
|
|  | [getName()](#getName--) | Gibt den lesbaren Namen dieses Schriftstils zurück. |
|
|  | [isBold()](#isBold--) | Gibt true zurück, wenn das Bold‑Bit gesetzt ist. |
|
|  | [isItalic()](#isItalic--) | Gibt true zurück, wenn das Italic‑Bit gesetzt ist. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Vereinigung (C#-Operator +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Differenz (C#-Operator -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Parst einen Schriftstilnamen in FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Erstellt eine FontStyles‑Instanz aus Bold/Italic‑Flags.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isBold | boolesch |  |
| isItalic | boolesch |  |

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


Konvertiert einen Stilwert in eine menschenlesbare Zeichenkette.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stil | int | der Schriftstilwert |
|

**Returns:**
java.lang.String - eine Zeichenkettenrepräsentation des Schriftstils

### getName() {#getName--}
```
public String getName()
```


Gibt den lesbaren Namen dieses Schriftstils zurück.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Gibt true zurück, wenn das Bold‑Bit gesetzt ist.


**Returns:**
boolesch
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Gibt true zurück, wenn das Italic‑Bit gesetzt ist.


**Returns:**
boolesch
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolesch
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


Vereinigung (C#-Operator +)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| erste | com.groupdocs.viewer.fonts.FontStyles |  |
| zweite | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Differenz (C#-Operator -)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minuend | com.groupdocs.viewer.fonts.FontStyles |  |
| subtrahend | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Parst einen Schriftstilnamen in FontStyles.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stil | java.lang.String |  |
| geparst | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true bei Erfolg, false andernfalls.

