---
title: WordProcessingSubstitutedFontInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Encapsulates metadata and binary data of one substituted font used in a WordProcessing document via GroupDocs.Viewer.
type: docs
weight: 18
url: /nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Encapsulates metadata and binary data of one substituted font used in a WordProcessing document via GroupDocs.Viewer. Immutable class.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Constructor to initialize all fields. |
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Returns the family name of the substituted font (never null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Returns the family name of the original font (never null). |
| [getStyle()](#getStyle--) | Returns the style of the original font. |
| [getContent()](#getContent--) | Returns the binary content of the substituted font (never null). |
| [getFormat()](#getFormat--) | Returns the font format of the substituted font. |
| [toString()](#toString--) | Returns a string describing this substituted font: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Equality based on original family, substituted family, and style. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialize this font as a @font-face CSS rule using a utility method. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Constructor to initialize all fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFamilyName | java.lang.String | The original font name (not found on system) |
| substitutedFamilyName | java.lang.String | The substituted font name (available) |
| style | com.groupdocs.viewer.fonts.FontStyles | Font style (Regular, Bold, Italic, BoldItalic) |
| content | byte[] | Binary content of substituted font (never null) |
| format | int | Font format (TrueType, OpenType, etc.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Returns the family name of the substituted font (never null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Returns the family name of the original font (never null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Returns the style of the original font.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Returns the binary content of the substituted font (never null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Returns the font format of the substituted font.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returns a string describing this substituted font: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equality based on original family, substituted family, and style. Required for usage in HashSet or HashMap like C\# IEqualityComparer.

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
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialize this font as a @font-face CSS rule using a utility method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer |  |

