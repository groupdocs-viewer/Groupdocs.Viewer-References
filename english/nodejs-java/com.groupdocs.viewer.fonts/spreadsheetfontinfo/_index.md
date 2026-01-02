---
title: SpreadsheetFontInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Encapsulates metainfo and binary data of one font from the Spreadsheet document loaded into the Viewer instance.
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Encapsulates metainfo and binary data of one font from the Spreadsheet document, loaded into the Viewer instance. Spreadsheet documents cannot have embedded fonts, so this particular font, if returned by the Viewer.getAllFonts() method, is installed in the operating system where GroupDocs.Viewer is running.
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Family name of the font, without style, never null or empty. |
| [getStyle()](#getStyle--) | Style of this font \\u2014 may be Regular, Bold, Italic, or BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Indicates whether the font is a single strikeout. |
| [isUnderline()](#isUnderline--) | Indicates whether the font has an underline. |
| [getColor()](#getColor--) | Color of this font. |
| [getCharset()](#getCharset--) | Character set of this font. |
| [getContent()](#getContent--) | Content of this font as a byte array. |
| [getFormat()](#getFormat--) | Format of this font. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font info as a @font-face at-rule and writes it to the specified writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Family name of the font, without style, never null or empty.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Style of this font \\u2014 may be Regular, Bold, Italic, or BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indicates whether the font is a single strikeout.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indicates whether the font has an underline.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Color of this font.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Character set of this font.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Content of this font as a byte array. May be null if only meta info is available.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format of this font.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializes this font info as a @font-face at-rule and writes it to the specified writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | Device to write serialized text data into. |

