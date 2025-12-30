---
title: WordProcessingOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering word processing documents.
type: docs
weight: 38
url: /nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Provides options for rendering word processing documents.

The WordProcessingOptions class provides options for rendering word processing documents in the GroupDocs.Viewer component. It encapsulates settings and parameters that can be used to control the rendering process and output format for word processing files. For details, see the [documentation][].

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


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Initializes a new instance of the  WordProcessingOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Retrieves the page size for rendering HTM and HTML files. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Sets the page size for rendering HTM and HTML files. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indicates whether tracked changes (revisions) rendering is enabled. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Sets whether tracked changes (revisions) rendering is enabled. |
| [getLeftMargin()](#getLeftMargin--) | Retrieves the left page margin for HTML rendering. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Sets the left page margin for HTML rendering. |
| [getRightMargin()](#getRightMargin--) | Gets the right page margin for HTML rendering. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Sets the right page margin for HTML rendering. |
| [getTopMargin()](#getTopMargin--) | Retrieves the top page margin for HTML rendering. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Sets the top page margin for HTML rendering. |
| [getBottomMargin()](#getBottomMargin--) | Bottom page margin (for HTML rendering only) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Sets the bottom page margin for HTML rendering. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian scripts, Latin-based or Cyrillic-based scripts. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indicates whether table of contents navigation should be disabled when rendering to HTML or PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Sets whether table of contents navigation should be disabled when rendering to HTML or PDF. |
| [isUpdateFields()](#isUpdateFields--) | Gets a value determining if fields of certain types should be updated before saving the input WordProcessing document to the HTML, PDF, PNG, or JPEG output formats. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Sets a value determining if fields of certain types should be updated before saving the input WordProcessing document to the HTML, PDF, PNG, or JPEG output formats. |
| [equals(Object o)](#equals-java.lang.Object-) | Check if the options are changed. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initializes a new instance of the  WordProcessingOptions  class. Contains options for rendering word processing documents. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Retrieves the page size for rendering HTM and HTML files.

When using the default page size, some content may not fit into the page frame. To fit the contents, you can set a larger page size, such as A3, using [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Sets the page size for rendering HTM and HTML files.

When using the default page size, some content may not fit into the page frame. To fit the contents, you can set a larger page size, such as A3, using [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | The size of the output page. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indicates whether tracked changes (revisions) rendering is enabled.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  if tracked changes rendering is enabled,  false  otherwise.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Sets whether tracked changes (revisions) rendering is enabled.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable tracked changes rendering,  false  to disable it. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Retrieves the left page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - the left page margin value.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Sets the left page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftMargin | java.lang.Double | The left page margin value to set. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Gets the right page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - the right page margin value.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Sets the right page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rightMargin | java.lang.Double | The right page margin value to set. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Retrieves the top page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - the top page margin.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Sets the top page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topMargin | java.lang.Double | The top page margin to set. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Bottom page margin (for HTML rendering only)

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - the bottom page margin.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Sets the bottom page margin for HTML rendering.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bottomMargin | java.lang.Double | The bottom page margin to set. |

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

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indicates whether table of contents navigation should be disabled when rendering to HTML or PDF. When this option is set to true, for HTML rendering, relative links from the table of contents will be replaced with span tags, removing functionality but preserving visual appearance. For PDF rendering, the table of contents will be rendered as plain text without links.

**Returns:**
boolean - True if table of content navigation is disabled; otherwise, false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Sets whether table of contents navigation should be disabled when rendering to HTML or PDF. When this option is set to true, for HTML rendering, relative links from the table of contents will be replaced with span tags, removing functionality but preserving visual appearance. For PDF rendering, the table of contents will be rendered as plain text without links.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Indicates whether table of content navigation should be disabled. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Gets a value determining if fields of certain types should be updated before saving the input WordProcessing document to the HTML, PDF, PNG, or JPEG output formats. Default value for this property is true \\u2014 fields will be updated before saving.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Sets a value determining if fields of certain types should be updated before saving the input WordProcessing document to the HTML, PDF, PNG, or JPEG output formats. Default value for this property is true \\u2014 fields will be updated before saving.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateFields | boolean |  |

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
