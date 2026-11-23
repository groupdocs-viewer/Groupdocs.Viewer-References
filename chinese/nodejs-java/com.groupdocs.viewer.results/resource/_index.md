---
title: "Resource"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 HTML 资源，例如字体、样式、图像或图形。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

表示 HTML 资源，例如字体、样式、图像或图形。

Resource 类表示在 GroupDocs.Viewer 组件中用于 HTML 渲染的资源。它可以表示各种类型的资源，例如字体、样式、图像或图形，这些资源在渲染过程中会被包含或引用到生成的 HTML 输出中。

示例用法：

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | 创建 Resource 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileName()](#getFileName--) | 返回资源的文件名。 |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | 设置资源的文件名。 |
| [isNested()](#isNested--) | 返回资源是否位于另一个资源内部，例如位于 CSS 或 SVG 资源中的字体资源。 |
| [setNested(boolean nested)](#setNested-boolean-) | 设置资源是否位于另一个资源内部。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


创建 Resource 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 资源文件名。 |
| 嵌套 | boolean | 指示资源是否位于另一个资源内部，例如位于 CSS 或 SVG 资源中的字体资源。 |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


返回资源的文件名。

**Returns:**
java.lang.String - 资源的文件名。
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


设置资源的文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 资源的新文件名。 |

### isNested() {#isNested--}
```
public final boolean isNested()
```


返回资源是否位于另一个资源内部，例如位于 CSS 或 SVG 资源中的字体资源。

**Returns:**
boolean - 资源是否位于另一个资源内部。
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


设置资源是否位于另一个资源内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 嵌套 | boolean | 资源是否应设置为嵌套。 |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 当前对象的字符串表示。
