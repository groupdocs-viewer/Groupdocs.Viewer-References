---
title: "SearchOption"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "現在のフォルダーのみを検索するか、現在のフォルダーとすべてのサブフォルダーを検索するかを指定します。"
type: docs
weight: 21
url: /ja/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

現在のフォルダーのみ検索するか、現在のフォルダーとすべてのサブフォルダーも検索するかを指定します。


SearchOption 列挙体は、GroupDocs.Viewer API におけるフォント検索操作の範囲を指定するために使用されます。


使用例:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | 検索に現在のフォルダーのみを含めます。 |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | 検索に現在のフォルダーとすべてのサブフォルダーを含めます。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


検索に現在のフォルダーのみを含めます。


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


検索に現在のフォルダーとすべてのサブフォルダーを含めます。


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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
