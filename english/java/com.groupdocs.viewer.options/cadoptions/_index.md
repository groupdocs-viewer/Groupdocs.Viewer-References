---
title: CadOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering CAD drawings.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Provides options for rendering CAD drawings.
## Methods

| Method | Description |
| --- | --- |
| [getPc3File()](#getPc3File--) | PC3 - plotter configuration file |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | PC3 - plotter configuration file |
| [forRenderingByScaleFactor(float scaleFactor)](#forRenderingByScaleFactor-float-) | Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by scale factor. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by height. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width and height. |
| [getScaleFactor()](#getScaleFactor--) | Values higher than 1 will enlarge output result; values between 0 and 1 will make output result smaller. |
| [getWidth()](#getWidth--) | The width of the output result in pixels. |
| [getHeight()](#getHeight--) | The height of the output result in pixels. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets image background color |
| [setBackgroundColor(Color mBackgroundColor)](#setBackgroundColor-java.awt.Color-) | Sets image background color |
| [getTiles()](#getTiles--) | The drawing regions to render. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | The drawing regions to render. |
| [isRenderLayouts()](#isRenderLayouts--) | Indicates whether layouts from CAD document should be rendered. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Indicates whether layouts from CAD document should be rendered. |
| [getLayoutName()](#getLayoutName--) | The name of the specific layout to render. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | The name of the specific layout to render. |
| [getLayers()](#getLayers--) | The CAD drawing layers to render. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | The CAD drawing layers to render. |
### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


PC3 - plotter configuration file

**Returns:**
java.lang.String
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


PC3 - plotter configuration file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pc3File | java.lang.String |  |

### forRenderingByScaleFactor(float scaleFactor) {#forRenderingByScaleFactor-float-}
```
public static CadOptions forRenderingByScaleFactor(float scaleFactor)
```


Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by scale factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleFactor | float | Values higher than 1 will enlarge output result; values between 0 and 1 will make output result smaller. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - New instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - New instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | int | The height of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - New instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initializes new instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the output result in pixels. |
| height | int | The height of the output result in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - New instance of [CadOptions](../../com.groupdocs.viewer.options/cadoptions) class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final float getScaleFactor()
```


Values higher than 1 will enlarge output result; values between 0 and 1 will make output result smaller.

**Returns:**
float
### getWidth() {#getWidth--}
```
public final int getWidth()
```


The width of the output result in pixels.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


The height of the output result in pixels.

**Returns:**
int
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets image background color

**Returns:**
java.awt.Color - Image background color
### setBackgroundColor(Color mBackgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color mBackgroundColor)
```


Sets image background color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mBackgroundColor | java.awt.Color | Image background color |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


The drawing regions to render.

--------------------

This option supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file type. The  RenderLayouts (\#isRenderLayouts().isRenderLayouts()/\#setRenderLayouts(boolean).setRenderLayouts(boolean)) and  LayoutName (\#getLayoutName().getLayoutName()/\#setLayoutName(String).setLayoutName(String)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile>
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


The drawing regions to render.

--------------------

This option supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file type. The  RenderLayouts (\#isRenderLayouts().isRenderLayouts()/\#setRenderLayouts(boolean).setRenderLayouts(boolean)) and  LayoutName (\#getLayoutName().getLayoutName()/\#setLayoutName(String).setLayoutName(String)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> |  |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Indicates whether layouts from CAD document should be rendered.

--------------------

This option applies only to CAD drawings that support layouts [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF) and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX); By default only Model is rendered.

**Returns:**
boolean
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Indicates whether layouts from CAD document should be rendered.

--------------------

This option applies only to CAD drawings that support layouts [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF) and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX); By default only Model is rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


The name of the specific layout to render. Layout name is case-sensitive.

--------------------

This option applies only to CAD drawings that support layouts [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF) and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX); By default only Model is rendered.

**Returns:**
java.lang.String
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


The name of the specific layout to render. Layout name is case-sensitive.

--------------------

This option applies only to CAD drawings that support layouts [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF) and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX); By default only Model is rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


The CAD drawing layers to render.

--------------------

By default all layers are rendered; Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer>
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


The CAD drawing layers to render.

--------------------

By default all layers are rendered; Layer names are case-sensitive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> |  |

