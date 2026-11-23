---
title: "SearchOption"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。"
type: docs
weight: 21
url: /zh/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。


SearchOption 枚举用于指定 GroupDocs.Viewer API 中字体搜索操作的范围。


示例用法：

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | 在搜索中仅包含当前文件夹。 |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | 在搜索中包含当前文件夹及所有子文件夹。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


在搜索中仅包含当前文件夹。


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


在搜索中包含当前文件夹及所有子文件夹。


### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
