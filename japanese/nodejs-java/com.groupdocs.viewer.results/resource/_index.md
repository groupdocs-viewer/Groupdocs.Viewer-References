---
title: "Resource"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "HTML リソース（フォント、スタイル、画像、またはグラフィックなど）を表します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

フォント、スタイル、画像、またはグラフィックなどの HTML リソースを表します。

Resource クラスは、GroupDocs.Viewer コンポーネントの HTML レンダリングで使用されるリソースを表します。フォント、スタイル、画像、またはグラフィックなど、レンダリングプロセス中に生成された HTML 出力に含まれる、または参照されるさまざまなタイプのリソースを表すことができます。

使用例:

```

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
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | リソース クラスの新しいインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFileName()](#getFileName--) | リソースのファイル名を返します。 |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | リソースのファイル名を設定します。 |
| [isNested()](#isNested--) | リソースが別のリソース内に存在するかどうかを返します。例: CSS または SVG リソース内に存在するフォントリソース。 |
| [setNested(boolean nested)](#setNested-boolean-) | リソースが別のリソース内に存在するかどうかを設定します。 |
| [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


リソース クラスの新しいインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | リソースのファイル名。 |
| ネストされた | boolean | リソースが別のリソース内に存在するかどうかを示します。例: CSS または SVG リソース内に存在するフォントリソース。 |

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
| fileName | java.lang.String | リソースの新しいファイル名。 |

### isNested() {#isNested--}
```
public final boolean isNested()
```


リソースが別のリソース内に存在するかどうかを返します。例: CSS または SVG リソース内に存在するフォントリソース。

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
| ネストされた | boolean | リソースをネストとして設定すべきかどうか。 |

### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトの文字列表現。
