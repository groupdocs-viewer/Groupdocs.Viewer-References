---
title: WordProcessingOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering word processing documents.
type: docs
weight: 35
url: /java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Provides options for rendering word processing documents.

The WordProcessingOptions class provides options for rendering word processing documents in the GroupDocs.Viewer component. It encapsulates settings and parameters that can be used to control the rendering process and output format for word processing files.

Example usage:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Initializes a new instance of the  WordProcessingOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indicates whether tracked changes (revisions) rendering is enabled. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Sets whether tracked changes (revisions) rendering is enabled. |
| [getLeftMargin()](#getLeftMargin--) | Retrieves the left page margin for HTML rendering. |
| [setLeftMargin(Float leftMargin)](#setLeftMargin-java.lang.Float-) | Sets the left page margin for HTML rendering. |
| [getRightMargin()](#getRightMargin--) | Gets the right page margin for HTML rendering. |
| [setRightMargin(Float rightMargin)](#setRightMargin-java.lang.Float-) | Sets the right page margin for HTML rendering. |
| [getTopMargin()](#getTopMargin--) | Retrieves the top page margin for HTML rendering. |
| [setTopMargin(Float topMargin)](#setTopMargin-java.lang.Float-) | Sets the top page margin for HTML rendering. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts. |
| [getBottomMargin()](#getBottomMargin--) | Bottom page margin (for HTML rendering only) |
| [setBottomMargin(Float bottomMargin)](#setBottomMargin-java.lang.Float-) | Sets the bottom page margin for HTML rendering. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if the options are changed. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initializes a new instance of the  WordProcessingOptions  class.

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indicates whether tracked changes (revisions) rendering is enabled.

**Returns:**
boolean -  true  if tracked changes rendering is enabled,  false  otherwise.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Sets whether tracked changes (revisions) rendering is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable tracked changes rendering,  false  to disable it. |

### getLeftMargin() {#getLeftMargin--}
```
public Float getLeftMargin()
```


Retrieves the left page margin for HTML rendering.

**Returns:**
java.lang.Float - the left page margin value.
### setLeftMargin(Float leftMargin) {#setLeftMargin-java.lang.Float-}
```
public void setLeftMargin(Float leftMargin)
```


Sets the left page margin for HTML rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftMargin | java.lang.Float | The left page margin value to set. |

### getRightMargin() {#getRightMargin--}
```
public Float getRightMargin()
```


Gets the right page margin for HTML rendering.

**Returns:**
java.lang.Float - the right page margin value.
### setRightMargin(Float rightMargin) {#setRightMargin-java.lang.Float-}
```
public void setRightMargin(Float rightMargin)
```


Sets the right page margin for HTML rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rightMargin | java.lang.Float | The right page margin value to set. |

### getTopMargin() {#getTopMargin--}
```
public Float getTopMargin()
```


Retrieves the top page margin for HTML rendering.

**Returns:**
java.lang.Float - the top page margin.
### setTopMargin(Float topMargin) {#setTopMargin-java.lang.Float-}
```
public void setTopMargin(Float topMargin)
```


Sets the top page margin for HTML rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topMargin | java.lang.Float | The top page margin to set. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts.

**Returns:**
boolean - True if OpenType features are enabled, false otherwise.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | True to enable OpenType features, false otherwise. |

### getBottomMargin() {#getBottomMargin--}
```
public Float getBottomMargin()
```


Bottom page margin (for HTML rendering only)

**Returns:**
java.lang.Float - the bottom page margin.
### setBottomMargin(Float bottomMargin) {#setBottomMargin-java.lang.Float-}
```
public void setBottomMargin(Float bottomMargin)
```


Sets the bottom page margin for HTML rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bottomMargin | java.lang.Float | The bottom page margin to set. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Check if the options are changed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare for equality. |

**Returns:**
boolean -  true  if the options are equal to the specified object,  false  otherwise.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Computes the hash code value for this object. The hash code is based on the internal state of the object and is used in hash-based data structures such as hash maps and hash sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - the hash code value for this object.
