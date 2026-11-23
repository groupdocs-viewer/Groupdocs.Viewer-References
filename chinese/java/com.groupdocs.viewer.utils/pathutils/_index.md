---
title: "PathUtils"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "PathUtils 类提供用于处理文件路径的实用方法。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils 类提供用于处理文件路径的实用方法。


PathUtils 类包含静态方法，允许您执行各种操作
在 GroupDocs.Viewer 组件中的文件路径上。


示例用法：

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | 使用分隔符组合路径部分。 |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | 获取文件名。 |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


使用分隔符组合路径部分。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | params | java.lang.String[] | 路径部分 |
|

**Returns:**
java.lang.String - 结果路径

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


获取文件名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 路径 | java.lang.String | 路径 |
|

**Returns:**
java.lang.String - 文件名

