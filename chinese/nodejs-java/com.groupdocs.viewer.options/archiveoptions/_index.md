---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于渲染存档文件的选项。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

提供用于渲染存档文件的选项。

ArchiveOptions 类表示一组可用于在查看器模块中配置归档文件渲染的选项。它允许您自定义渲染过程的各个方面，例如每页的项目数量等。

示例用法：

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | 使用默认设置创建 ArchiveOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFolder()](#getFolder--) | 获取归档内部用于渲染的文件夹。 |
| [setFolder(String value)](#setFolder-java.lang.String-) | 设置将在渲染时使用的存档内部文件夹。 |
| [getFileName()](#getFileName--) | 获取将在标题中显示的文件名。 |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | 设置将在标题中显示的文件名。 |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


使用默认设置创建 ArchiveOptions 类的新实例。

### getFolder() {#getFolder--}
```
public final String getFolder()
```


获取归档内部用于渲染的文件夹。

默认情况下，GroupDocs.Viewer 会渲染存档中所有文件夹的项目。要渲染特定文件夹的项目，请设置此属性。代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - 要渲染的文件夹。
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


设置将在渲染时使用的存档内部文件夹。

默认情况下，GroupDocs.Viewer 会渲染存档中所有文件夹的项目。要渲染特定文件夹的项目，请设置此属性。代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 要渲染的文件夹。 |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


获取将在标题中显示的文件名。

默认情况下，GroupDocs.Viewer 在每页的标题中显示存档文件名。要更改或隐藏此名称，请设置此属性。更多信息和代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


设置将在标题中显示的文件名。

默认情况下，GroupDocs.Viewer 在每页的标题中显示存档文件名。要更改或隐藏此名称，请设置此属性。更多信息和代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | 要显示的文件名。 |

