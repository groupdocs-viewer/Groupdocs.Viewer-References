---
title: "FileName"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示存档中文件的名称。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

表示存档中文件的名称。

FileName 类封装了文件的名称，不包含任何路径或目录信息。它提供了操作和检索文件名信息的方法。

示例用法：

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | 初始化一个新的 FileName 类实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EMPTY](#EMPTY) | 表示一个空文件名。 |
| [SOURCE](#SOURCE) | 表示源文件的名称。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | 返回当前对象的字符串表示形式。 |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


初始化一个新的 FileName 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | 文件的名称。 |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


表示一个空文件名。

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


表示源文件的名称。

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


返回当前对象的字符串表示形式。

**Returns:**
java.lang.String - 当前对象的字符串表示形式。
