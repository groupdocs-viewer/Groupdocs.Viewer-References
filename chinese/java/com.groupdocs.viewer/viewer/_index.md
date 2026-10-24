---
title: "Viewer"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示控制文档渲染过程的主类。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

表示控制文档渲染过程的主类。


Viewer 类是使用 GroupDocs.Viewer 组件渲染文档的入口点。
它提供方法和选项，以从各种来源加载文档、自定义渲染过程，并以不同格式检索渲染输出。


示例用法：

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | 初始化 Viewer 类的新实例。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | 返回关于视图和文档的特定信息。 |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | 返回关于视图和文档的特定信息。 |
|
|  | [getAttachments()](#getAttachments--) | 返回文档中包含的附件。 |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | 返回文档中包含的附件。 |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | 将附件文件保存到目标流。 |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | 将附件文件保存到目标流。 |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | 创建所有文档页面的视图。 |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | 创建所有文档页面的视图。 |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | 创建特定文档页面的视图。 |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | 创建特定文档页面的视图。 |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | 创建特定文档页面的视图。 |
|
|  | [getAllFonts()](#getAllFonts--) | 返回已加载文档中使用的所有字体，包括文档本身嵌入的字体以及操作系统中已安装并在文档中使用的系统字体。 |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | 根据提供的选项在已加载文档中执行文本搜索并突出显示匹配项（如果找到）。 |
|
|  | [getFileInfo()](#getFileInfo--) | 返回有关文件的信息，例如文件类型以及指示文件是否加密的标志。 |
|
|  | [close()](#close--) | 释放文件流和受管理的内部资源。 |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


初始化 Viewer 类的新实例。


更多关于 GroupDocs.Viewer 支持的文件类型：
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 返回可读流的方法。 |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | leaveOpen | boolean | true 表示在 Viewer 对象被释放后保持流打开；否则为 false。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 可读流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | leaveOpen | boolean | true 表示在 Viewer 对象被释放后保持流打开；否则为 false。 |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|
|  | leaveOpen | boolean | true 表示在 Viewer 对象被释放后保持流打开；否则为 false。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 文件流。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|
|  | leaveOpen | boolean | true 表示在 Viewer 对象被释放后保持流打开；否则为 false。 |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


初始化 Viewer 类的新实例。


更多关于 GroupDocs.Viewer 支持的文件类型： [GroupDocs.Viewer 支持的文档格式](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | url | java.net.URL | 要加载到 Viewer 的文件的 URL。 |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | url | java.net.URL | 要加载到 Viewer 的文件的 URL。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | url | java.net.URL | 要加载到 Viewer 的文件的 URL。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | url | java.net.URL | 要加载到 Viewer 的文件的 URL。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


初始化 Viewer 类的新实例。


此构造函数允许您创建一个 Viewer 对象，以从 [FileReader](../../com.groupdocs.viewer.interfaces/filereader) 查看文档，并使用指定的 [ViewerSettings](../../com.groupdocs.viewer/viewersettings)。
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | 包含要加载到 Viewer 中的文档的 [FileReader](../../com.groupdocs.viewer.interfaces/filereader)。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | 要应用于 Viewer 的 [ViewerSettings](../../com.groupdocs.viewer/viewersettings)。 |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


初始化 Viewer 类的新实例。


提供使用 GroupDocs.Viewer 加载和查看文档的功能。


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | 文件读取器。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


初始化 Viewer 类的新实例。
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要渲染的文件路径。 |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要渲染的文件路径。 |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要渲染的文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要渲染的文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要渲染的文件路径。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要渲染的文件路径。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 要渲染的文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


初始化 Viewer 类的新实例。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | 要渲染的文件路径。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 文档加载选项。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 设置。 |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


返回关于视图和文档的特定信息。
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | 视图信息选项。 |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


返回关于视图和文档的特定信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | 视图信息选项。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 用于取消操作的取消令牌。 |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


返回文档中包含的附件。
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - 文档中包含的附件。

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


返回文档中包含的附件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 用于取消操作的取消令牌。 |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - 文档中包含的附件。

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


将附件文件保存到目标流。
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | 附件。 |
|
|  | 目标 | java.io.OutputStream | 可写流。 |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


将附件文件保存到目标流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | 附件。 |
|
|  | 目标 | java.io.OutputStream | 可写流。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 用于取消操作的取消令牌。 |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


创建所有文档页面的视图。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 视图选项。 |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


创建所有文档页面的视图。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 视图选项。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 用于取消渲染过程的取消令牌。 |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


创建特定文档页面的视图。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 视图选项。 |
|
|  | pageNumber | int | 要查看的页码。 |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


创建特定文档页面的视图。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 视图选项。 |
|
|  | pageNumbers | int[] | 要查看的页码列表。 |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


创建特定文档页面的视图。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 视图选项。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 用于取消渲染过程的取消令牌。 |
|
|  | pageNumbers | int[] | 要查看的页码列表。 |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


返回已加载文档中使用的所有字体，包括文档本身嵌入的字体以及操作系统中已安装并在文档中使用的系统字体。

有关详细信息，请参阅
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - 非空列表，包含加载到此 [Viewer](../../com.groupdocs.viewer/viewer) 实例中的文档使用的所有字体。

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


根据提供的选项在已加载文档中执行文本搜索并突出显示匹配项（如果找到）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 选项 | com.groupdocs.viewer.options.SearchHighlightOptions | 搜索和高亮选项，包括要搜索的文本短语。不能为空。 |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


返回有关文件的信息，例如文件类型以及指示文件是否加密的标志。
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


释放文件流和受管理的内部资源。


