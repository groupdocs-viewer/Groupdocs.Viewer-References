---
title: "Resource"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "フォント、スタイル、画像、またはグラフィックなどの HTML リソースを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

フォント、スタイル、画像、またはグラフィックなどの HTML リソースを表します。


Resource クラスは、GroupDocs.Viewer コンポーネントで HTML レンダリングに使用されるリソースを表します。
フォント、スタイル、画像、またはグラフィックなど、含まれるさまざまなタイプのリソースを表すことができます
またはレンダリングプロセス中に生成された HTML 出力で参照されます。


使用例:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | 新しいインスタンスを作成します |
Resource
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileName()](#getFileName--) | リソースのファイル名を返します。 |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | リソースのファイル名を設定します。 |
|
|  | [isNested()](#isNested--) | リソースが別のリソース内に存在するかどうかを返します。例: CSS や SVG リソース内に存在するフォントリソース。 |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | リソースが別のリソース内に存在するかどうかを設定します。 |
|
|  | [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


新しいインスタンスを作成します
Resource
クラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileName | java.lang.String | リソースのファイル名。 |
|
|  | ネスト | boolean | リソースが別のリソース内に存在するかどうかを示します。例: CSS や SVG リソース内に存在するフォントリソース。 |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


リソースのファイル名を返します。


**Returns:**
java.lang.String - リソースのファイル名。

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


リソースのファイル名を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileName | java.lang.String | リソースの新しいファイル名。 |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


リソースが別のリソース内に存在するかどうかを返します。例: CSS や SVG リソース内に存在するフォントリソース。


**Returns:**
boolean - リソースが別のリソース内に存在するかどうか。

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


リソースが別のリソース内に存在するかどうかを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ネスト | boolean | リソースをネストとして設定すべきかどうか。 |
|

### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。


**Returns:**
java.lang.String - 現在のオブジェクトの文字列表現。

