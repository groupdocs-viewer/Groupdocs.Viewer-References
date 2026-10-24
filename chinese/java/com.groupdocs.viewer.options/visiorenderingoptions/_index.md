---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "包含用于渲染 Visio 文档的选项。"
type: docs
weight: 36
url: /zh/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

包含用于渲染 Visio 文档的选项。


VisioRenderingOptions 类提供用于处理和渲染 Visio 文件的选项
在 GroupDocs.Viewer 组件中。它封装了可用于的设置和参数
以控制 Visio 文档的渲染过程和输出格式。
详情请参见[文档](../https://docs.groupdocs.com/viewer/java/render-visio-documents/)。


示例用法：

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | 初始化一个新的实例 |
VisioRenderingOptions
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | 仅渲染 Visio 图形，排除图表。 |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | 设置标志以仅渲染 Visio 图形，排除图表。 |
|
|  | [getFigureWidth()](#getFigureWidth--) | 获取图形的宽度。 |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | 设置图形的宽度。 |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


初始化一个新的实例
VisioRenderingOptions
类。


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


仅渲染 Visio 图形，排除图表。
详情请参见[文档](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)。


**Returns:**
boolean - 如果仅渲染 Visio 图形则为 true，否则为 false。

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


设置标志以仅渲染 Visio 图形，排除图表。
详情请参见[文档](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true 表示仅渲染 Visio 图形，false 表示包含图表。 |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


获取图形的宽度。高度将自动计算。


**Returns:**
int - 图形的宽度。

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


设置图形的宽度。高度将自动计算。


***Note:** Default value is 100.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | figureWidth | int | 图形的宽度。 |
|

