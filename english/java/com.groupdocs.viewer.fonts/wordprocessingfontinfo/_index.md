---
title: WordProcessingFontInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Encapsulates metainfo and binary data of one font from the WordProcessing document loaded into the Viewer instance.
type: docs
weight: 17
url: /java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Encapsulates metainfo and binary data of one font from the WordProcessing document, loaded into the Viewer instance. This font is used in the document content and is embedded inside the document itself or is installed in the operating system where GroupDocs.Viewer is running.

Immutable class. Its instances are produced and returned by the GroupDocs.Viewer public API and normally should not be created by the user. For details, see the documentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Family name of the font, without style, never null or empty. |
| [getAltFamilyName()](#getAltFamilyName--) | Alternative family name of the font. |
| [getStyle()](#getStyle--) | Style of the font \\u2014 may be Regular, Bold, Italic, or BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Indicates whether this font is embedded inside the document (true) or a system font (false). |
| [getFormat()](#getFormat--) | Format of this font. |
| [getContent()](#getContent--) | Content of this font as a byte array, or null if unavailable. |
| [getCharset()](#getCharset--) | Character set of this font. |
| [toString()](#toString--) | Returns debug info about this font in the following template: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font info as a @font-face CSS rule and writes it to the specified writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Family name of the font, without style, never null or empty.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Alternative family name of the font. If missing, returns empty string.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Style of the font \\u2014 may be Regular, Bold, Italic, or BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indicates whether this font is embedded inside the document (true) or a system font (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format of this font. If there is only metainfo and binary content is missing, may return FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Content of this font as a byte array, or null if unavailable.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Character set of this font.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returns debug info about this font in the following template: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializes this font info as a @font-face CSS rule and writes it to the specified writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | Writer to receive the serialized CSS. |

