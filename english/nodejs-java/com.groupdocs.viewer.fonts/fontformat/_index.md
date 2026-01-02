---
title: FontFormat
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents all font formats which may be present in the UsedFontInfo class.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Represents all font formats, which may be present in the UsedFontInfo class.
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | Unknown or invalid font format. |
| [TrueType](#TrueType) | TrueType font format (TTF). |
| [OpenType](#OpenType) | OpenType font format (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection font format (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType font format (EOT). |
## Methods

| Method | Description |
| --- | --- |
| [toString(int format)](#toString-int-) | Converts a format value to a human-readable string. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Unknown or invalid font format.

### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType font format (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType font format (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection font format (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded OpenType font format (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Converts a format value to a human-readable string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | the font format value |

**Returns:**
java.lang.String - a string representation of the font format
