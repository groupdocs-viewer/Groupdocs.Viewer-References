---
title: PresentationFontInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Encapsulates metadata and binary data of a font used in a Presentation document loaded into the Viewer instance.
type: docs
weight: 15
url: /java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Encapsulates metadata and binary data of a font used in a Presentation document, loaded into the Viewer instance. This font is used in the document content and may be embedded inside the document itself or installed in the operating system where GroupDocs.Viewer is running.
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Gets the font family name (never null or empty). |
| [getStyle()](#getStyle--) | Gets the style of the font: Regular, Bold, Italic, or BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Indicates whether this font is embedded inside the document loaded into the Viewer instance. |
| [getFormat()](#getFormat--) | Gets the font format (TrueType, OpenType, etc.). |
| [getContent()](#getContent--) | Gets the binary font content, or null if font data is unavailable. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font info into CSS @font-face rule using the specified writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gets the font family name (never null or empty).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gets the style of the font: Regular, Bold, Italic, or BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indicates whether this font is embedded inside the document loaded into the Viewer instance. Note: Spreadsheet documents cannot contain embedded fonts, so for them this always returns false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Gets the font format (TrueType, OpenType, etc.). If only metadata is available, returns FontFormat.Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Gets the binary font content, or null if font data is unavailable.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializes this font info into CSS @font-face rule using the specified writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | writer to write CSS into (must not be null) |

