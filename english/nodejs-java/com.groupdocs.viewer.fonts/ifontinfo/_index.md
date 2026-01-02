---
title: IFontInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Common interface for all fonts that can be extracted from document formats PDF WordProcessing Spreadsheet and Presentation.
type: docs
weight: 20
url: /nodejs-java/com.groupdocs.viewer.fonts/ifontinfo/
---```
public interface IFontInfo
```

Common interface for all fonts that can be extracted from document formats: PDF, WordProcessing, Spreadsheet, and Presentation.
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Family name of the font as a string. |
| [getStyle()](#getStyle--) | Style of the font \\u2014 Regular, Bold, Italic, or BoldItalic. |
| [getFormat()](#getFormat--) | Format of the font \\u2014 TrueType, TrueType Collection, OpenType, Embedded OpenType, or Unknown. |
| [getContent()](#getContent--) | Binary content of the font, or null if not available. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializes this font info as a @font-face at-rule and writes it to the specified writer. |
### getFamilyName() {#getFamilyName--}
```
public abstract String getFamilyName()
```


Family name of the font as a string.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public abstract FontStyles getStyle()
```


Style of the font \\u2014 Regular, Bold, Italic, or BoldItalic. Some document formats may have only Regular.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getFormat() {#getFormat--}
```
public abstract int getFormat()
```


Format of the font \\u2014 TrueType, TrueType Collection, OpenType, Embedded OpenType, or Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Binary content of the font, or null if not available.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public abstract void serializeToCss(Writer output)
```


Serializes this font info as a @font-face at-rule and writes it to the specified writer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.Writer | destination writer |

