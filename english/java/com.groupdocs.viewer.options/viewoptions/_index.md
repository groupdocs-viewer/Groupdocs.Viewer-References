---
title: ViewOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides rendering options.
type: docs
weight: 31
url: /java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Provides rendering options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWatermark()](#getWatermark--) | The text watermark applied to each page. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | The text watermark applied to each page. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Applies clockwise rotation to the page. |
| [getPageRotations()](#getPageRotations--) | The page rotations. |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


The text watermark applied to each page.

--------------------

In case both \#setWatermark(Watermark).setWatermark(Watermark) and \#getPageRotations().getPageRotations() are specified than watermark will be applied to the rotated pages.

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark)
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


The text watermark applied to each page.

--------------------

In case both  ViewOptions.Watermark  and \#getPageRotations().getPageRotations() are specified than watermark will be applied to the rotated pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) |  |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Applies clockwise rotation to the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | The rotation value. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


The page rotations.

--------------------

In case both  ViewOptions.Watermark (\#getWatermark().getWatermark()/\#setWatermark(Watermark).setWatermark(Watermark)) and \#PageRotations.PageRotations are specified than watermark will be applied to the rotated pages.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation>
