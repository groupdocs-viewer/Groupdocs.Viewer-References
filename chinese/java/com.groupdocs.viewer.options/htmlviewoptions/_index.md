---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供将文档渲染为 HTML 格式的选项。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

提供将文档渲染为 HTML 格式的选项。


HtmlViewOptions 类封装了额外的设置和参数
可用于在 GroupDocs.Viewer 组件中控制文档渲染为 HTML 格式。


有关详细信息，请参阅 [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) 及其子项。


示例用法：

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | 确定是否已启用响应式渲染。 |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | 设置是否启用响应式渲染。 |
|
|  | [isMinify()](#isMinify--) | 检查是否已启用 HTML 内容和 HTML 资源的压缩。 |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | 设置是否启用 HTML 内容和 HTML 资源的压缩。 |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | 启用将整个文档渲染为单个 HTML 文件。 |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | 启用将整个文档渲染为单个 HTML 文件。 |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | 返回输出图像的最大宽度（像素）。 |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 设置输出图像的最大宽度（像素）。 |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | 获取输出图像的最大高度（像素）。 |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 设置输出图像的最大高度（像素）。 |
|
|  | [getImageWidth()](#getImageWidth--) | 获取输出图像的宽度（像素）。 |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | 设置输出图像的宽度（像素）。 |
|
|  | [getImageHeight()](#getImageHeight--) | 在将单个图像转换为 HTML 时，获取输出图像的高度（像素）。 |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | 在将单个图像转换为 HTML 时，设置输出图像的高度（像素）。 |
|
|  | [isForPrinting()](#isForPrinting--) | 检查输出 HTML 是否应针对打印进行优化。 |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | 设置输出 HTML 是否应针对打印进行优化。 |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | 确定是否从 HTML 文档中排除字体。 |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | 设置是否从 HTML 文档中排除字体。 |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | 检索要从 HTML 文档中排除的字体名称列表。 |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | 设置要从 HTML 文档中排除的字体名称列表。 |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | 允许在渲染包含脚本的输入文档时，从生成的 HTML 文档中的链接中移除 JavaScript 源代码。 |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | 设置在渲染包含脚本的输入文档时，从生成的 HTML 文档中的链接中移除 JavaScript 源代码的权限。 |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | 检索用于估计 Word 或 Email 文档保存进度的回调函数。 |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | 设置用于估计 Word 或 Email 文档保存进度的回调函数。 |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | 初始化一个新的实例 |
HtmlViewOptions
类。
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | 初始化一个新的实例 |
HtmlViewOptions
类。
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | 初始化一个新的实例 |
HtmlViewOptions
类。
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | 初始化一个新的实例 |
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。
|
|  | [forExternalResources()](#forExternalResources--) | 初始化新的实例 |
HtmlViewOptions
类。
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | 初始化一个新的实例 |
HtmlViewOptions
类。
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


确定是否已启用响应式渲染。
响应式网页在不同屏幕尺寸的设备上能够良好渲染。


响应式设计旨在使网页在各种设备上良好渲染。要使用响应式布局进行渲染，请将此属性设置为 true。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)。


**Returns:**
布尔型 - 如果启用了响应式渲染则为 true，否则为 false。

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


设置是否启用响应式渲染。
响应式网页在不同屏幕尺寸的设备上能够良好渲染。


响应式设计旨在使网页在各种设备上良好渲染。要使用响应式布局进行渲染，请将此属性设置为 true。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true 表示启用响应式渲染，false 表示禁用。 |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


检查是否已启用 HTML 内容和 HTML 资源的压缩。


压缩输出内容（HTML、CSS 和 SVG）是优化 HTML 文件的一种方式。要实现此功能，请将此属性设置为 true。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/minify-html/)。


**Returns:**
布尔型 - 如果启用了压缩则为 true，否则为 false。

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


设置是否启用 HTML 内容和 HTML 资源的压缩。


压缩输出内容（HTML、CSS 和 SVG）是优化 HTML 文件的一种方式。要实现此功能，请将此属性设置为 true。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/minify-html/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true 表示启用压缩，false 表示禁用。 |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


启用将整个文档渲染为单个 HTML 文件。

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


启用将整个文档渲染为单个 HTML 文件。

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


返回输出图像的最大宽度（像素）。
***Note:** This value is used when converting a single image to HTML.
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - 输出图像的最大宽度。

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


设置输出图像的最大宽度（像素）。
***Note:** This value is used when converting a single image to HTML.
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageMaxWidth | int | 输出图像的最大宽度。 |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


获取输出图像的最大高度（像素）。
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - 输出图像的最大高度。

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


设置输出图像的最大高度（像素）。
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageMaxHeight | int | 输出图像的最大高度。 |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


获取输出图像的宽度（像素）。


***Note:** This value is applicable only when converting a single image to HTML.*
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)。


**Returns:**
int - 输出图像的宽度。

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


设置输出图像的宽度（像素）。


***Note:** This value is applicable only when converting a single image to HTML.*
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageWidth | int | 输出图像的宽度。 |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


在将单个图像转换为 HTML 时，获取输出图像的高度（像素）。


有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)。


**Returns:**
int - 输出图像的高度（像素）。

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


在将单个图像转换为 HTML 时，设置输出图像的高度（像素）。


有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageHeight | int | 输出图像的高度（像素）。 |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


检查输出 HTML 是否应针对打印进行优化。


启用此选项可将输出的 HTML 页面转换为矢量 SVG 格式。
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/)。


**Returns:**
boolean -  true  如果输出 HTML 应该针对打印进行优化，则为 true；否则为 false。

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


设置输出 HTML 是否应针对打印进行优化。


启用此选项可将输出的 HTML 页面转换为矢量 SVG 格式。
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  用于优化输出 HTML 以便打印，  false  否则。 |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


确定是否从 HTML 文档中排除字体。


默认情况下，GroupDocs.Viewer 会将文档中使用的字体嵌入到 HTML 中。若要阻止此行为，请将此属性设置为 true。
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)。


**Returns:**
boolean -  true  如果应排除字体，则为 true；否则为 false。

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


设置是否从 HTML 文档中排除字体。


默认情况下，GroupDocs.Viewer 会将文档中使用的字体嵌入到 HTML 中。若要阻止此行为，请将此属性设置为 true。
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  用于排除字体，  false  否则。 |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


检索要从 HTML 文档中排除的字体名称列表。


此选项仅在演示文稿中受支持。
在 HTML 文档中包含字体可提升输出视图的稳定性，但会增加渲染结果的大小。
使用此选项在稳定性和输出大小之间取得平衡。
包含在大多数系统上流行且已安装的字体名称。


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) 选项已禁用。*
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)。


**Returns:**
java.util.List<java.lang.String> - 要从 HTML 文档中排除的字体名称列表。

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


设置要从 HTML 文档中排除的字体名称列表。


此选项仅在演示文稿中受支持。
在 HTML 文档中包含字体可提升输出视图的稳定性，但会增加渲染结果的大小。
使用此选项在稳定性和输出大小之间取得平衡。
包含在大多数系统上流行且已安装的字体名称。


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) 选项已禁用。*
有关详细信息和代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.util.List<java.lang.String> | 要从 HTML 文档中排除的字体名称列表。 |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


允许在渲染包含脚本的输入文档时，从生成的 HTML 文档中的链接中移除 JavaScript 源代码。默认情况下已启用（true）。


有关移除 JavaScript 的详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)。


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


设置在渲染包含脚本的输入文档时，从生成的 HTML 文档中的链接中移除 JavaScript 源代码的权限。默认情况下已启用（true）。


有关移除 JavaScript 的详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


检索用于估计 Word 或 Email 文档保存进度的回调函数。


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 用于估计文档保存进度的回调。

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


设置用于估计 Word 或 Email 文档保存进度的回调函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 用于估计文档保存进度的回调。 |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。


***Note:** The method takes a 
CreatePageStream
参数，即用于实例化用于写入输出页面数据的流的方法。*
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | 释放由分配给  createPageStream  参数的方法创建的流的方法。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带嵌入资源的 HTML 的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 实现创建和释放输出页面流方法的工厂。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


初始化一个新的实例
HtmlViewOptions
类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


初始化一个新的实例
HtmlViewOptions
类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 文件路径格式，例如 'page_{0}.html'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


初始化一个新的实例
HtmlViewOptions
类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | 文件路径格式，例如 'page_{0}.html'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | 释放  createPageStream  方法的方法。 |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | 创建 HTML 资源 URL 的方法。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 实例化用于写入输出页面数据的流的方法。 |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | 实例化用于写入输出 HTML 资源数据的流的方法。 |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | 创建 HTML 资源 URL 的方法。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | 释放  createPageStream  方法的方法。 |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | 释放由  createResourceStream  方法创建的流的方法。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


初始化一个新的实例
HtmlViewOptions
用于渲染为带外部资源的 HTML 的类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 实现创建和释放输出页面流方法的工厂。 |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | 实现创建资源 URL 以及实例化/释放输出 HTML 资源流方法的工厂。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


初始化新的实例
HtmlViewOptions
类。


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

输出文件将放置在应用程序的当前工作目录中。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)。

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


初始化一个新的实例
HtmlViewOptions
类。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 文件路径格式，例如 'page_{0}.html'。 |
|
|  | resourceFilePathFormat | java.lang.String | 资源文件路径格式，例如 'page_{0}/resource_{1}'。 |
|
|  | resourceUrlFormat | java.lang.String | 资源 URL 格式，例如 'page_{0}/resource_{1}'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
