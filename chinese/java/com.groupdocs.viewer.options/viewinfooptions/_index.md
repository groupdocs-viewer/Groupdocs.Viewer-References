---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于检索视图信息的选项。"
type: docs
weight: 34
url: /zh/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

提供用于检索视图信息的选项。


ViewInfoOptions 类封装了额外的设置和参数，
可用于检索 GroupDocs.Viewer 组件中视图的信息。


示例用法：

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | 指示是否已启用文本提取。 |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | 设置指示是否启用文本提取的标志。 |
|
|  | [getMaxWidth()](#getMaxWidth--) | 返回用于渲染为 PNG/JPG 的输出图像的最大宽度。 |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 设置输出图像的最大宽度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [getMaxHeight()](#getMaxHeight--) | 返回用于渲染为 PNG/JPG 的输出图像的最大高度。 |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 设置输出图像的最大高度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [getWidth()](#getWidth--) | 输出图像的宽度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [setWidth(int width)](#setWidth-int-) | 输出图像的宽度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [getHeight()](#getHeight--) | 输出图像的高度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [setHeight(int height)](#setHeight-int-) | 输出图像的高度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
|
|  | [forHtmlView()](#forHtmlView--) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 HTML 时检索视图信息的类。
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 HTML 时检索视图信息的类。
|
|  | [forJpgView()](#forJpgView--) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 JPG 时检索视图信息的类。
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 JPG 时检索视图信息的类。
|
|  | [forPngView()](#forPngView--) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 PNG 时检索视图信息的类。
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | 初始化一个新的实例 |
ViewInfoOptions
用于在渲染为 PNG 时检索视图信息的类。
|
|  | [forPdfView()](#forPdfView--) | 初始化 ViewInfoOptions 类的新实例，以在渲染为 PDF 时检索视图信息。 |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | 初始化一个新的实例 |
ViewInfoOptions
基于 [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) 对象的类。
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | 初始化一个新的实例 |
ViewInfoOptions
基于 [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) 对象的类。
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | 初始化一个新的实例 |
ViewInfoOptions
基于 [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) 对象的类。
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | 基于 PdfViewOptions 对象初始化 [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) 类的新实例。 |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


指示是否已启用文本提取。
使用此属性获取源文档中包含的文本及其坐标。然后可以使用这些数据在图像上添加可选文本，或在基于图像的渲染中实现文本搜索。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/)。


**Returns:**
boolean - 如果启用了文本提取则为 True，否则为 false。

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


设置指示是否启用文本提取的标志。
使用此属性获取源文档中包含的文本及其坐标。然后可以使用这些数据在图像上添加可选文本，或在基于图像的渲染中实现文本搜索。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | extractText | boolean | True 表示启用文本提取，false 表示禁用。 |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


返回用于渲染为 PNG/JPG 的输出图像的最大宽度。
使用此属性设置最大输出图像宽度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)。如果设置了此属性，则此属性将被忽略。


**Returns:**
int - 输出图像的最大宽度。

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


设置输出图像的最大宽度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置最大输出图像宽度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)。如果设置了此属性，则此属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxWidth | int | 输出图像的最大宽度。 |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


返回用于渲染为 PNG/JPG 的输出图像的最大高度。
使用此属性设置最大输出图像高度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)。如果设置了此属性，则此属性将被忽略。


**Returns:**
int - 输出图像的最大高度。

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


设置输出图像的最大高度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置最大输出图像高度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/)。如果设置了此属性，则此属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxHeight | int | 输出图像的最大高度。 |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


输出图像的宽度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置输出图像宽度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)。如果设置了此属性，则该属性将被忽略。


**Returns:**
int - 图像的宽度。

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


输出图像的宽度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置输出图像宽度（以像素为单位）。代码示例请参阅 [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)。如果设置了此属性，则该属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | width | int | 图像的宽度。 |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


输出图像的高度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置输出图像的高度（以像素为单位）。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)。如果设置了此属性，则该属性将被忽略。


**Returns:**
int - 图像的高度。

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


输出图像的高度（以像素为单位，仅用于渲染为 PNG/JPG）。
使用此属性设置输出图像的高度（以像素为单位）。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/)。如果设置了此属性，则该属性将被忽略。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | height | int | 图像的高度。 |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 HTML 时检索视图信息的类。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 HTML 时检索视图信息的类。


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderSinglePage | boolean | 启用在单页上渲染 HTML 内容。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 JPG 时检索视图信息的类。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 JPG 时检索视图信息的类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | extractText | boolean | 启用文本提取。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 PNG 时检索视图信息的类。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


初始化一个新的实例
ViewInfoOptions
用于在渲染为 PNG 时检索视图信息的类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | extractText | boolean | 启用文本提取。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


初始化 ViewInfoOptions 类的新实例，以在渲染为 PDF 时检索视图信息。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


初始化一个新的实例
ViewInfoOptions
基于 [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) 对象的类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML 视图选项。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


初始化一个新的实例
ViewInfoOptions
基于 [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) 对象的类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG 视图选项。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


初始化一个新的实例
ViewInfoOptions
基于 [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) 对象的类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG 视图选项。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


基于 PdfViewOptions 对象初始化 [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF 视图选项。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

