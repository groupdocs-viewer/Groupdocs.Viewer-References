---
title: FontStyles
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents 4 possible styles of the font used in the document Regular Bold Italic or Bold Italic.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Represents 4 possible styles of the font, used in the document: Regular, Bold, Italic, or Bold Italic.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Creates a FontStyles instance from bold/italic flags. |
## Fields

| Field | Description |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Methods

| Method | Description |
| --- | --- |
| [toString(int style)](#toString-int-) | Converts a style value to a human-readable string. |
| [getName()](#getName--) | Returns readable name of this font style. |
| [isBold()](#isBold--) | Returns true if bold bit is set. |
| [isItalic()](#isItalic--) | Returns true if italic bit is set. |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Union (C\# operator +) |
| [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Difference (C\# operator -) |
| [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Parses a font style name to FontStyles. |
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Creates a FontStyles instance from bold/italic flags.

**Parameters:**
| Parameter | Type | Description |
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


Converts a style value to a human-readable string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | int | the font style value |

**Returns:**
java.lang.String - a string representation of the font style
### getName() {#getName--}
```
public String getName()
```


Returns readable name of this font style.

**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Returns true if bold bit is set.

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Returns true if italic bit is set.

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
| Parameter | Type | Description |
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


Union (C\# operator +)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | com.groupdocs.viewer.fonts.FontStyles |  |
| second | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Difference (C\# operator -)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| minuend | com.groupdocs.viewer.fonts.FontStyles |  |
| subtrahend | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Parses a font style name to FontStyles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | java.lang.String |  |
| parsed | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true on success, false otherwise.
