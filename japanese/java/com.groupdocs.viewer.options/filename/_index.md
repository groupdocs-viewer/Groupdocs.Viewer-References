---
title: "FileName"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "アーカイブ内のファイル名を表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

アーカイブ内のファイル名を表します。


FileName クラスは、パスやディレクトリ情報なしでファイル名をカプセル化します。
ファイル名に関する情報を操作および取得するためのメソッドを提供します。


使用例:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | 新しいインスタンスを初期化します |
FileName
クラス。
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [EMPTY](#EMPTY) | 空のファイル名を表します。 |
|
|  | [SOURCE](#SOURCE) | ソースファイルの名前を表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | 現在のオブジェクトの文字列表現を返します。 |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


新しいインスタンスを初期化します
FileName
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileName | java.lang.String | ファイルの名前。 |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


空のファイル名を表します。


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


ソースファイルの名前を表します。


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


現在のオブジェクトの文字列表現を返します。


**Returns:**
java.lang.String - 現在のオブジェクトの文字列表現。

