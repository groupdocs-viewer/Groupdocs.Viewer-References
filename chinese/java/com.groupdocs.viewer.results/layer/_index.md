---
title: "Layer"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示 CAD 绘图中包含的图层。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

表示 CAD 绘图中包含的图层。


该 Layer 接口定义了在 CAD 绘图中访问和操作图层的契约。
在 GroupDocs.Viewer 组件中。它提供检索信息的方法，例如图层名称，
可见性，以及其他属性。


示例用法：

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 检索图层的名称。 |
|
|  | [setName(String name)](#setName-java.lang.String-) | 设置图层的名称。 |
|
|  | [isVisible()](#isVisible--) | 检查图层的可见性。 |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | 设置图层的可见性。 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 检查此对象是否等于提供的对象。 |
|
### getName() {#getName--}
```
public abstract String getName()
```


检索图层的名称。


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - 图层的名称。

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


设置图层的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 名称 | java.lang.String | 图层的新名称。 |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


检查图层的可见性。


已关闭或冻结的 CAD 绘图图层是不可见的。
要渲染不可见的图层，请使用 [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-) 选项。


**Returns:**
boolean -  true  如果图层可见，则为 true；否则为 false。

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


设置图层的可见性。


如果
true
，图层将可见；如果
false
，则它将隐藏。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | isVisible | boolean | 图层是否应当可见。 |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


检查此对象是否等于提供的对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 其他 | java.lang.Object | 要比较的对象。 |
|

**Returns:**
boolean -  true  如果对象相等，则为 true；否则为 false。

