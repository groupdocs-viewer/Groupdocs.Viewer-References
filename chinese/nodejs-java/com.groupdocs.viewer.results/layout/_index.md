---
title: "布局"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 CAD 绘图中包含的布局。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

表示 CAD 绘图中包含的布局。

Layout 接口定义了在 GroupDocs.Viewer 组件的 CAD 图纸中访问和操作布局的契约。它提供了检索布局名称、尺寸及其他属性等信息的方法。

示例用法：

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 检索布局的名称。 |
| [setName(String name)](#setName-java.lang.String-) | 设置布局的名称。 |
| [getWidth()](#getWidth--) | 检索布局的宽度。 |
| [setWidth(double width)](#setWidth-double-) | 设置布局的宽度。 |
| [getHeight()](#getHeight--) | 检索布局的高度。 |
| [setHeight(double height)](#setHeight-double-) | 设置布局的高度。 |
| [equals(Object other)](#equals-java.lang.Object-) | 检查此对象是否等于提供的对象。 |
### getName() {#getName--}
```
public abstract String getName()
```


检索布局的名称。

**Returns:**
java.lang.String - 布局的名称。
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


设置布局的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 要为布局设置的名称。 |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


检索布局的宽度。

**Returns:**
double - 布局的宽度。
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


设置布局的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | double | 要为布局设置的宽度。 |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


检索布局的高度。

**Returns:**
double - 布局的高度。
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


设置布局的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| height | double | 要为布局设置的高度。 |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


检查此对象是否等于提供的对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | java.lang.Object | 用于比较的对象。 |

**Returns:**
boolean -  true  如果对象相等，则为 true；否则为 false。
