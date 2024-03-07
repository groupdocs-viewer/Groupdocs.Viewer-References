---
title: ViewOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides rendering options.
type: docs
weight: 32
url: /nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Provides rendering options.

The ViewOptions class extends the BaseViewOptions class and serves as a base class for rendering options in the GroupDocs.Viewer component. It encapsulates common settings and parameters that can be used for rendering various types of documents into different formats.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWatermark()](#getWatermark--) | Gets the text watermark applied to each page. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Sets the text watermark to be applied to each page. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Applies a clockwise rotation to the specified page. |
| [getPageRotations()](#getPageRotations--) | Retrieves the page rotations. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | To prevent creating the instance just to check that it is empty |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Gets the text watermark applied to each page.

In case both \#setWatermark(Watermark).setWatermark(Watermark) and \#getPageRotations().getPageRotations() are specified, the watermark will be applied to the rotated pages.

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Sets the text watermark to be applied to each page.

In case both  ViewOptions.Watermark  and \#getPageRotations().getPageRotations() are specified, the watermark will be applied to the rotated pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | The text watermark to be set. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Applies a clockwise rotation to the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | The rotation value. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Retrieves the page rotations.

If both [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) and  getPageRotations()  are specified, the watermark will be applied to the rotated pages.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - a map containing the page numbers as keys and their corresponding rotations as values.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


To prevent creating the instance just to check that it is empty

**Returns:**
boolean
