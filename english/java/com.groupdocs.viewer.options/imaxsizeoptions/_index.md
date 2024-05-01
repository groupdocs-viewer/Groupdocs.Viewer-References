---
title: IMaxSizeOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Limits of image size options interface.
type: docs
weight: 37
url: /java/com.groupdocs.viewer.options/imaxsizeoptions/
---```
public interface IMaxSizeOptions
```

Limits of image size options interface.

The IMaxSizeOptions interface defines the limits of image size options in the GroupDocs.Viewer component. It serves as a contract for classes that provide maximum size constraints for rendering images.
## Methods

| Method | Description |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Retrieves the maximum width of an output image in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Sets the maximum width of an output image in pixels. |
| [getMaxHeight()](#getMaxHeight--) | Retrieves the maximum height of an output image in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Sets the maximum height of an output image in pixels. |
### getMaxWidth() {#getMaxWidth--}
```
public abstract int getMaxWidth()
```


Retrieves the maximum width of an output image in pixels.

**Returns:**
int - the maximum width of the output image.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public abstract void setMaxWidth(int maxWidth)
```


Sets the maximum width of an output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | The maximum width of the output image. |

### getMaxHeight() {#getMaxHeight--}
```
public abstract int getMaxHeight()
```


Retrieves the maximum height of an output image in pixels.

**Returns:**
int - the maximum height of the output image.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public abstract void setMaxHeight(int maxHeight)
```


Sets the maximum height of an output image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxHeight | int | The maximum height of the output image. |

