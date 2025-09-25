---
title: UsedFontInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents metainfo and binary data of one font used in the content of the document loaded into the Viewer instance.
type: docs
weight: 14
url: /java/com.groupdocs.viewer.fonts/usedfontinfo/
---
**Inheritance:**
java.lang.Object
```
public final class UsedFontInfo
```

Represents metainfo and binary data of one font, used in the content of the document, loaded into the Viewer instance.

Immutable class. Its instances are produced and returned by the GroupDocs.Viewer public API and normally should not be created by the user.

For details, see: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of the font, without style, never null or empty string. |
| [getStyle()](#getStyle--) | Style of the font \\u2014 may be Regular, Bold, Italic, or Bold Italic. |
| [isEmbedded()](#isEmbedded--) | Indicates whether this font is embedded inside the document, loaded into the Viewer instance (true), or it is a system font (false). |
| [getFormat()](#getFormat--) | Format of this font. |
| [getContent()](#getContent--) | Content of this font as a byte array. |
| [getCharset()](#getCharset--) | Character set of this font. |
| [toString()](#toString--) | Returns a debug info string about this font in format: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font info as a @font-face at-rule and writes it to the specified Writer. |
| [detectFormat(FontResourceBase fontResource)](#detectFormat-com.groupdocs.viewer.htmlcss.resources.fonts.FontResourceBase-) | Detects font format from a parsed font resource. |
### getName() {#getName--}
```
public String getName()
```


Name of the font, without style, never null or empty string.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public int getStyle()
```


Style of the font \\u2014 may be Regular, Bold, Italic, or Bold Italic. For the PDF documents may be only Regular style.

**Returns:**
int
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indicates whether this font is embedded inside the document, loaded into the Viewer instance (true), or it is a system font (false). Spreadsheet documents cannot hold embedded fonts, so for them this property always returns false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format of this font. Documents may use fonts in the next formats: TrueType, TrueType Collection, OpenType, Embedded OpenType. If only metainfo is available, but no binary content, this property returns FontFormat\#Unknown.Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Content of this font as a byte array. If there is only metainfo about this font, but its binary content is unavailable, this property returns null.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Character set of this font. Returns valid number only for WordProcessing and Spreadsheet formats. For all other formats returns 0 (zero).

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Returns a debug info string about this font in format: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializes this font info as a @font-face at-rule and writes it to the specified Writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | Writer into which the serialized text data should be written |

### detectFormat(FontResourceBase fontResource) {#detectFormat-com.groupdocs.viewer.htmlcss.resources.fonts.FontResourceBase-}
```
public static byte detectFormat(FontResourceBase fontResource)
```


Detects font format from a parsed font resource. In real implementation it would check concrete font classes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontResource | com.groupdocs.viewer.htmlcss.resources.fonts.FontResourceBase |  |

**Returns:**
byte
