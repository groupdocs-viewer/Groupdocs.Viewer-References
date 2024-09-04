---
title: CadOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering CAD drawings.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Provides options for rendering CAD drawings.

The CadOptions class encapsulates various settings and parameters that can be used to control the rendering of CAD drawings in the GroupDocs.Viewer component.

For more information and code examples, see the [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] and [Specify rendering options for CAD files][].

Example usage:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Fields

| Field | Description |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPc3File()](#getPc3File--) | Retrieves the PC3 (Plotter Configuration) file associated with the plotter. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Sets the PC3 (Plotter Configuration) file associated with the plotter. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initializes a new instance of the  CadOptions  class for rendering by scale factor. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initializes a new instance of the  CadOptions  class for rendering by width. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initializes a new instance of the  CadOptions  class for rendering by height. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initializes a new instance of the  CadOptions  class for rendering by width and height. |
| [getScaleFactor()](#getScaleFactor--) | Gets the scale factor for rendering. |
| [getWidth()](#getWidth--) | Gets the width of the output result in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the output result in pixels. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the background color of the image. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Gets the background color of the image. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Sets the background color of the image. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Sets the background color of the image. |
| [getTiles()](#getTiles--) | Gets the drawing regions to render. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Sets the drawing regions to render. |
| [isRenderLayouts()](#isRenderLayouts--) | Indicates whether layouts from the CAD document should be rendered. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Sets whether layouts from the CAD document should be rendered. |
| [getLayoutName()](#getLayoutName--) | Gets the name of the specific layout to render. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Sets the name of the specific layout to render. |
| [getLayers()](#getLayers--) | Gets the CAD drawing layers to render. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Gets the CAD drawing layers to render. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Setting this flag to true enables a special performance-oriented conversion mode for all formats within the CAD family. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Setting this flag to true enables a special performance-oriented conversion mode for all formats within the CAD family. |
| [equals(Object o)](#equals-java.lang.Object-) | Checks if this CadOptions object is equal to another object. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Retrieves the PC3 (Plotter Configuration) file associated with the plotter.

**Returns:**
java.lang.String - the PC3 file path.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Sets the PC3 (Plotter Configuration) file associated with the plotter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pc3File | java.lang.String | The PC3 file path. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initializes a new instance of the  CadOptions  class for rendering by scale factor.

For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleFactor | double | The scale factor for rendering. Values greater than 1 will enlarge the output result, while values between 0 and 1 will make the output result smaller. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initializes a new instance of the  CadOptions  class for rendering by width.

For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initializes a new instance of the  CadOptions  class for rendering by height.

For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | int | The height of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initializes a new instance of the  CadOptions  class for rendering by width and height.

For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the output result in pixels. |
| height | int | The height of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Gets the scale factor for rendering. Values higher than 1 will enlarge the output result, while values between 0 and 1 will make the output result smaller.

**Returns:**
double - the scale factor for rendering.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of the output result in pixels.

**Returns:**
int - the width of the output result.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height of the output result in pixels.

**Returns:**
int - the height of the output result.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the background color of the image.

**Returns:**
java.awt.Color - the background color of the image.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Gets the background color of the image.

**Returns:**
java.lang.String - the background color of the image in 0xFFFFFF format.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Sets the background color of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| backgroundColor | java.awt.Color | The background color of the image. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Sets the background color of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorName | java.lang.String | The background color name of the image. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Gets the drawing regions to render.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - the list of drawing regions to render.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Sets the drawing regions to render.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | The list of drawing regions to render. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Indicates whether layouts from the CAD document should be rendered.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  if layouts should be rendered,  false  otherwise.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Sets whether layouts from the CAD document should be rendered.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to render layouts,  false  otherwise. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Gets the name of the specific layout to render. The layout name is case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - the name of the specific layout to render.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Sets the name of the specific layout to render. The layout name is case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the specific layout to render. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Gets the CAD drawing layers to render.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - the CAD drawing layers.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Gets the CAD drawing layers to render.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | The CAD drawing layers. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Setting this flag to true enables a special performance-oriented conversion mode for all formats within the CAD family. In this mode, the conversion speed is much faster, but the quality of the resultant documents is significantly worse. By default, it is disabled (false). The quality of the resultant documents is the best possible at the expense of performance.

**Returns:**
boolean -  true  if performance-oriented conversion mode is enabled,  false  otherwise.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Setting this flag to true enables a special performance-oriented conversion mode for all formats within the CAD family. In this mode, the conversion speed is much faster, but the quality of the resultant documents is significantly worse. By default, it is disabled (false). The quality of the resultant documents is the best possible at the expense of performance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean |  true  to enable the performance-oriented conversion mode,  false  to disable it. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Checks if this CadOptions object is equal to another object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare with. |

**Returns:**
boolean -  true  if the objects are equal,  false  otherwise.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Computes the hash code value for this object. The hash code is based on the internal state of the object and is used in hash-based data structures such as hash maps and hash sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - the hash code value for this object.
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of this object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - a string representation of this object.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Returns a string representation of this object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | org.apache.commons.lang3.builder.ToStringStyle | The ToStringStyle to use for generating the string representation. |

**Returns:**
java.lang.String - a string representation of this object using the specified ToStringStyle.
