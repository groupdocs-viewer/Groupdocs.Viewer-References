---
title: "页面"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示可查看的单页。"
type: docs
weight: 21
url: /zh/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

表示可查看的单页。

Page 接口定义了在 GroupDocs.Viewer 组件中访问和操作可查看的单个页面的契约。它提供了检索页面编号、尺寸以及其他属性等信息的方法。

示例用法：

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 检索工作表或页面的名称。 |
| [setName(String name)](#setName-java.lang.String-) | 设置工作表或页面的名称。 |
| [getNumber()](#getNumber--) | 检索页面编号。 |
| [setNumber(int number)](#setNumber-int-) | 设置页面编号。 |
| [isVisible()](#isVisible--) | 检索页面可见性指示器。 |
| [setVisible(boolean visible)](#setVisible-boolean-) | 设置页面可见性指示器。 |
| [getWidth()](#getWidth--) | 检索以 JPG 或 PNG 形式查看时页面的宽度（像素）。 |
| [setWidth(int width)](#setWidth-int-) | 设置以 JPG 或 PNG 形式查看时页面的宽度（像素）。 |
| [getHeight()](#getHeight--) | 检索以 JPG 或 PNG 形式查看时页面的高度（像素）。 |
| [setHeight(int height)](#setHeight-int-) | 设置以 JPG 或 PNG 形式查看时页面的高度（像素）。 |
| [getLines()](#getLines--) | 检索在启用文本提取的情况下，以 JPG 或 PNG 形式查看时页面中包含的行。 |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | 设置在启用文本提取的情况下，以 JPG 或 PNG 形式查看时页面中包含的行。 |
### getName() {#getName--}
```
public abstract String getName()
```


检索工作表或页面的名称。

**Returns:**
java.lang.String - 工作表或页面的名称。
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


设置工作表或页面的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 要为工作表或页面设置的名称。 |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


检索页面编号。

**Returns:**
int - 页面编号。
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


设置页面编号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数字 | int | 要设置的页面编号。 |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


检索页面可见性指示器。

**Returns:**
boolean - 页面可见性指示器。
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


设置页面可见性指示器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 可见 | boolean | 如果页面可见则为 true，否则为 false。 |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


检索以 JPG 或 PNG 形式查看时页面的宽度（像素）。

**Returns:**
int - 页面宽度。
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


设置以 JPG 或 PNG 形式查看时页面的宽度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 要为页面设置的宽度。 |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


检索以 JPG 或 PNG 形式查看时页面的高度（像素）。

**Returns:**
int - 页面高度。
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


设置以 JPG 或 PNG 形式查看时页面的高度（像素）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| height | int | 要为页面设置的高度。 |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


检索在启用文本提取的情况下，以 JPG 或 PNG 形式查看时页面中包含的行。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - 页面中包含的行。
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


设置在启用文本提取的情况下，以 JPG 或 PNG 形式查看时页面中包含的行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | 要为页面设置的行列表。 |

