---
title: PdfFontInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Encapsulates meta-information and binary data of one font from a PDF document loaded into the Viewer instance.
type: docs
weight: 14
url: /java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Encapsulates meta-information and binary data of one font from a PDF document, loaded into the Viewer instance.

This font is used in the document content and is either:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Internal constructor used by PDF font extraction. |
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Gets the font family name. |
| [getStyle()](#getStyle--) | Gets the style of this font. |
| [isEmbedded()](#isEmbedded--) | Returns whether the font is embedded inside the PDF document. |
| [isInstalled()](#isInstalled--) | Returns whether the font is installed in the OS. |
| [getFormat()](#getFormat--) | Returns the file format of the font. |
| [getContent()](#getContent--) | Returns the binary content of the font. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font as a CSS  @font-face  rule. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Internal constructor used by PDF font extraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| familyName | java.lang.String | font family name |
| style | com.groupdocs.viewer.fonts.FontStyles | style (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true if the font is embedded in the PDF |
| isInstalled | boolean | true if the font is installed in the OS |
| content | byte[] | binary font data (nullable) |
| format | int | font file format |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gets the font family name.

**Returns:**
java.lang.String - family name string (never null or empty)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gets the style of this font.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - the font style
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Returns whether the font is embedded inside the PDF document.

**Returns:**
boolean - true if embedded
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Returns whether the font is installed in the OS.

**Returns:**
boolean - true if installed
### getFormat() {#getFormat--}
```
public int getFormat()
```


Returns the file format of the font.

**Returns:**
int - the font format enum
### getContent() {#getContent--}
```
public byte[] getContent()
```


Returns the binary content of the font.

**Returns:**
byte[] - byte array or null if not available
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializes this font as a CSS  @font-face  rule.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | writer to which CSS will be written |

