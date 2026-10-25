---
title: "PathUtils"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PathUtils クラスはファイルパスを扱うためのユーティリティメソッドを提供します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils クラスはファイルパスを扱うためのユーティリティメソッドを提供します。


PathUtils クラスは、さまざまな操作を実行できる静的メソッドを含んでいます
GroupDocs.Viewer コンポーネントのファイルパスに対して。


使用例:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | 区切り文字を使用してパスの部分を結合します。 |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | ファイル名を取得します。 |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


区切り文字を使用してパスの部分を結合します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | パラメータ | java.lang.String[] | パスの部分 |
|

**Returns:**
java.lang.String - 結果のパス

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


ファイル名を取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | パス | java.lang.String | パス |
|

**Returns:**
java.lang.String - ファイル名

