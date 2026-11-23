---
title: "ViewOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "包含渲染选项。"
type: docs
weight: 35
url: /zh/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

包含渲染选项。


ViewOptions 类扩展了 BaseViewOptions 类，并作为渲染选项的基类。
在 GroupDocs.Viewer 组件中。它封装了可用于的通用设置和参数。
用于将各种类型的文档渲染为不同的格式。


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | 获取应用于每页的文字水印。 |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | 设置要应用于每页的文字水印。 |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | 对指定页面执行顺时针旋转。 |
|
|  | [getPageRotations()](#getPageRotations--) | 检索页面旋转信息。 |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | 为了防止仅为检查实例是否为空而创建实例 |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


获取应用于每页的文字水印。


如果同时指定了 #setWatermark(Watermark).setWatermark(Watermark) 和 #getPageRotations().getPageRotations()，
水印将应用于已旋转的页面。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/add-text-watermark/)。


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


设置要应用于每页的文字水印。


如果两者都
ViewOptions.Watermark
并且指定了 #getPageRotations().getPageRotations()，
水印将应用于已旋转的页面。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/add-text-watermark/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | 要设置的文字水印。 |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


对指定页面执行顺时针旋转。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageNumber | int | 页码必须严格大于 0。 |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | 旋转值。 |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


检索页面旋转信息。


If both [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) and
getPageRotations()
已指定，
水印将应用于已旋转的页面。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/)。


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - 包含页码作为键及其对应旋转值的映射。

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


为了防止仅为检查实例是否为空而创建实例


**Returns:**
boolean
