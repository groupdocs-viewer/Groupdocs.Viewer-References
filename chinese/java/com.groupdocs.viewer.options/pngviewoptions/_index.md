---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供将文档渲染为 PNG 格式的选项。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

提供将文档渲染为 PNG 格式的选项。


PngViewOptions 类封装了可用于的附加设置和参数
以控制在 GroupDocs.Viewer 组件中将文档渲染为 PNG 格式。


示例用法：

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
有关详细信息，请参阅此 [page](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) 及其子页面。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | 初始化一个新的实例 |
PngViewOptions
类。
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 初始化一个新的实例 |
PngViewOptions
类。
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 初始化一个新的实例 |
PngViewOptions
类。
|
|  | [PngViewOptions()](#PngViewOptions--) | 初始化新的实例 |
PngViewOptions
类。
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | 初始化一个新的实例 |
PngViewOptions
类。
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | 初始化一个新的实例 |
PngViewOptions
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | 返回输出图像的最大宽度（像素）。 |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 设置输出图像的最大宽度（像素）。 |
|
|  | [getMaxHeight()](#getMaxHeight--) | 返回输出图像的最大高度（像素）。 |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 设置输出图像的最大高度（像素）。 |
|
|  | [isExtractText()](#isExtractText--) | 确定是否已启用文本提取。 |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | 启用或禁用文本提取。 |
|
|  | [getWidth()](#getWidth--) | 返回输出图像的宽度（像素）。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 设置输出图像的宽度（像素）。 |
|
|  | [getHeight()](#getHeight--) | 返回输出图像的高度（像素）。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 设置输出图像的高度（像素）。 |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | 检索用于估计文档保存进度的回调。 |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | 设置用于估计文档保存进度的回调。 |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


初始化一个新的实例
PngViewOptions
类。


有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


初始化一个新的实例
PngViewOptions
类。


有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | 释放由分配给 createPageStream 参数的方法创建的流的方法。 |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


初始化一个新的实例
PngViewOptions
类。


有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 实现创建和释放输出页面流方法的工厂。 |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


初始化新的实例
PngViewOptions
类。


此构造函数初始化新的实例
PngViewOptions

使用 \"p_{0}.png\" 作为输出文件的文件路径格式。
输出文件将放置在应用程序的当前工作目录中。
有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


初始化一个新的实例
PngViewOptions
类。


例如，如果文件路径格式为 'page_{0}.png'，输出文件将会
命名为 'page_1.png'、'page_2.png'，依此类推，基于页码。


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 文件路径格式，例如 'page_{0}.png'。 |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


初始化一个新的实例
PngViewOptions
类。


例如，如果文件路径格式为 'page_{0}.png'，输出文件将会
命名为 'page_1.png'、'page_2.png'，依此类推，基于页码。
有关代码示例，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | 文件路径格式，例如 'page_{0}.png'。 |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


返回输出图像的最大宽度（像素）。


使用此属性设置输出图像的最大宽度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)。
如果设置了该属性，则此属性将被忽略。


**Returns:**
int - 输出图像的最大宽度。

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


设置输出图像的最大宽度（像素）。


使用此属性设置输出图像的最大宽度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)。
如果设置了该属性，则此属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxWidth | int | 输出图像的最大宽度。 |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


返回输出图像的最大高度（像素）。


使用此属性设置输出图像的最大高度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)。
如果设置了该属性，则此属性将被忽略。


**Returns:**
int - 输出图像的最大高度。

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


设置输出图像的最大高度（像素）。


使用此属性设置输出图像的最大高度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)。
如果设置了该属性，则此属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxHeight | int | 输出图像的最大高度。 |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


确定是否已启用文本提取。


当您想在图像上添加可选择的文本层时，此选项可能会有用。
使用此属性获取源文档中包含的文本及其坐标。然后您可以使用这些数据在图像上添加可选择的文本，或在基于图像的渲染中实现文本搜索。
代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)。


**Returns:**
boolean -  如果启用了文本提取则为 true，否则为 false。

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


启用或禁用文本提取。


当您想在图像上添加可选择的文本层时，此选项可能会有用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  表示启用文本提取，false  表示禁用。 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


返回输出图像的宽度（像素）。


使用此属性设置输出图像的宽度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)。
如果设置了此属性，则该属性会被忽略。


**Returns:**
int - 输出图像的宽度。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置输出图像的宽度（像素）。


使用此属性设置输出图像的宽度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)。
如果设置了此属性，则该属性会被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 输出图像的宽度。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


返回输出图像的高度（像素）。


使用此属性设置输出图像的高度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)。
如果设置了此属性，则该属性会被忽略。


**Returns:**
int - 输出图像的高度。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置输出图像的高度（像素）。


使用此属性设置输出图像的高度（像素）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)。
如果设置了此属性，则该属性会被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 输出图像的高度。 |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


检索用于估计文档保存进度的回调。


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 用于估计文档保存进度的回调。

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


设置用于估计文档保存进度的回调。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 用于估计文档保存进度的回调。 |
|

