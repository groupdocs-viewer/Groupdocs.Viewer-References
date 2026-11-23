---
title: "CadOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供渲染 CAD 图纸的选项。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

提供渲染 CAD 图纸的选项。


CadOptions 类封装了可用于的各种设置和参数
以控制在 GroupDocs.Viewer 组件中渲染 CAD 图纸。


欲了解更多信息和代码示例，请参阅 [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) 和 [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/)。


示例用法：

````

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
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | 检索与绘图仪关联的 PC3 (Plotter Configuration) 文件。 |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | 设置与绘图仪关联的 PC3 (Plotter Configuration) 文件。 |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | 初始化一个新的实例 |
CadOptions
用于按比例因子渲染的类。
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | 初始化一个新的实例 |
CadOptions
用于按宽度渲染的类。
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | 初始化一个新的实例 |
CadOptions
用于按高度渲染的类。
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | 初始化一个新的实例 |
CadOptions
用于按宽度和高度渲染的类。
|
|  | [getScaleFactor()](#getScaleFactor--) | 获取渲染的比例因子。 |
|
|  | [getWidth()](#getWidth--) | 获取输出结果的宽度（像素）。 |
|
|  | [getHeight()](#getHeight--) | 获取输出结果的高度（像素）。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取图像的背景颜色。 |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | 获取图像的背景颜色。 |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | 设置图像的背景颜色。 |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | 设置图像的背景颜色。 |
|
|  | [getTiles()](#getTiles--) | 获取要渲染的绘图区域。 |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | 设置要渲染的绘图区域。 |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | 指示是否应渲染 CAD 文档中的布局。 |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | 设置是否渲染 CAD 文档中的布局。 |
|
|  | [getLayoutName()](#getLayoutName--) | 获取要渲染的特定布局的名称。 |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | 设置要渲染的特定布局的名称。 |
|
|  | [getLayers()](#getLayers--) | 获取要渲染的 CAD 绘图图层。 |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | 获取要渲染的 CAD 绘图图层。 |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | 将此标志设置为 true 可为 CAD 系列的所有格式启用一种专注于性能的特殊转换模式。 |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | 将此标志设置为 true 可为 CAD 系列的所有格式启用一种专注于性能的特殊转换模式。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | 检查此 CadOptions 对象是否等于另一个对象。 |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
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


检索与绘图仪关联的 PC3 (Plotter Configuration) 文件。


**Returns:**
java.lang.String - PC3 文件路径。

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


设置与绘图仪关联的 PC3 (Plotter Configuration) 文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pc3File | java.lang.String | PC3 文件路径。 |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


初始化一个新的实例
CadOptions
用于按比例因子渲染的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | scaleFactor | double | 渲染的比例因子。大于 1 的值会放大输出结果，而介于 0 和 1 之间的值会使输出结果变小。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


初始化一个新的实例
CadOptions
用于按宽度渲染的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | width | int | 输出结果的宽度（像素）。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


初始化一个新的实例
CadOptions
用于按高度渲染的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | height | int | 输出结果的高度（像素）。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


初始化一个新的实例
CadOptions
用于按宽度和高度渲染的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | width | int | 输出结果的宽度（像素）。 |
|
|  | height | int | 输出结果的高度（像素）。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


获取渲染的比例因子。
大于 1 的值会放大输出结果，而介于 0 和 1 之间的值会使输出结果变小。


**Returns:**
double - 渲染的比例因子。

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取输出结果的宽度（像素）。


**Returns:**
int - 输出结果的宽度。

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取输出结果的高度（像素）。


**Returns:**
int - 输出结果的高度。

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取图像的背景颜色。


**Returns:**
java.awt.Color - 图像的背景颜色。

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


获取图像的背景颜色。


**Returns:**
java.lang.String - 以 0xFFFFFF 格式表示的图像背景颜色。

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


设置图像的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | 图像的背景颜色。 |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


设置图像的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | colorName | java.lang.String | 图像的背景颜色名称。 |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


获取要渲染的绘图区域。
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
该
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
and
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) 选项将被忽略
在按瓦片渲染时.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - 要渲染的绘图区域列表。

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


设置要渲染的绘图区域。
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
该
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
and
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) 选项将被忽略
在按瓦片渲染时.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<com.groupdocs.viewer.options.Tile> | 要渲染的绘图区域列表。 |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


指示是否应渲染 CAD 文档中的布局。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
默认情况下，仅渲染模型。*


**Returns:**
boolean -  true  如果应渲染布局，则为 true；否则为 false。

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


设置是否渲染 CAD 文档中的布局。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
默认情况下，仅渲染模型。*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  表示渲染布局，  false  表示不渲染。 |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


获取要渲染的特定布局的名称。布局名称区分大小写。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
默认情况下，仅渲染模型。*


**Returns:**
java.lang.String - 要渲染的特定布局的名称。

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


设置要渲染的特定布局的名称。布局名称区分大小写。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
默认情况下，仅渲染模型。*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 要渲染的特定布局的名称。 |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


获取要渲染的 CAD 绘图图层。


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 绘图层。

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


获取要渲染的 CAD 绘图图层。
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 绘图图层。 |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


将此标志设置为 true 可为 CAD 系列中的所有格式启用一种专注于性能的特殊转换模式。在此模式下，转换速度更快，但生成文档的质量显著下降。默认情况下，该模式已禁用（false）。生成文档的质量在性能的代价下达到最佳可能水平。


**Returns:**
boolean -  true  如果已启用面向性能的转换模式，则为 true；否则为 false。

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


将此标志设置为 true 可为 CAD 系列中的所有格式启用一种专注于性能的特殊转换模式。在此模式下，转换速度更快，但生成文档的质量显著下降。默认情况下，该模式已禁用（false）。生成文档的质量在性能的代价下达到最佳可能水平。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  启用面向性能的转换模式，  false  禁用它。 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查此 CadOptions 对象是否等于另一个对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | o | java.lang.Object | 用于比较的对象。 |
|

**Returns:**
boolean -  true  如果对象相等，则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


计算此对象的哈希码值。哈希码基于
对象的内部状态，并用于基于哈希的数据结构
例如哈希映射和哈希集合。
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - 此对象的哈希码值。

### toString() {#toString--}
```
public String toString()
```


返回此对象的字符串表示形式。
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - 此对象的字符串表示形式。

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


返回此对象的字符串表示形式。
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 样式 | org.apache.commons.lang3.builder.ToStringStyle | 用于生成字符串表示形式的 ToStringStyle。 |
|

**Returns:**
java.lang.String - 使用指定的 ToStringStyle 的此对象的字符串表示形式。

