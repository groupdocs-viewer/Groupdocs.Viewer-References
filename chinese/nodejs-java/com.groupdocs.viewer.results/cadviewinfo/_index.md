---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 CAD 绘图的视图信息。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

表示 CAD 绘图的视图信息。

CadViewInfo 接口定义了在 GroupDocs.Viewer 组件中检索特定 CAD 图纸视图信息的契约。它提供了访问 CAD 图纸图层的方法。

示例用法：

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLayers()](#getLayers--) | 检索 CAD 图纸中的图层列表。 |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | 设置 CAD 图纸中的图层列表。 |
| [getLayouts()](#getLayouts--) | 检索 CAD 图纸中包含的布局列表。 |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | 设置 CAD 图纸中包含的布局列表。 |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


检索 CAD 图纸中的图层列表。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 图纸中的图层。
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


设置 CAD 图纸中的图层列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | java.util.List<com.groupdocs.viewer.results.Layer> | 要为 CAD 图纸设置的图层。 |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


检索 CAD 图纸中包含的布局列表。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD 图纸中的布局。
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


设置 CAD 图纸中包含的布局列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 布局 | java.util.List<com.groupdocs.viewer.results.Layout> | 要为 CAD 图纸设置的布局。 |

