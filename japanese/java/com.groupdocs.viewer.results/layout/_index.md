---
title: "レイアウト"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "CAD図面に含まれるレイアウトを表します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

CAD図面に含まれるレイアウトを表します。


Layout インターフェイスは、CAD 図面内のレイアウトにアクセスし操作するための契約を定義します。
GroupDocs.Viewer コンポーネント内で。レイアウト名などの情報を取得するメソッドを提供します、
寸法やその他のプロパティ。


使用例:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | レイアウトの名前を取得します。 |
|
|  | [setName(String name)](#setName-java.lang.String-) | レイアウトの名前を設定します。 |
|
|  | [getWidth()](#getWidth--) | レイアウトの幅を取得します。 |
|
|  | [setWidth(double width)](#setWidth-double-) | レイアウトの幅を設定します。 |
|
|  | [getHeight()](#getHeight--) | レイアウトの高さを取得します。 |
|
|  | [setHeight(double height)](#setHeight-double-) | レイアウトの高さを設定します。 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | このオブジェクトが提供されたオブジェクトと等しいかどうかを確認します。 |
|
### getName() {#getName--}
```
public abstract String getName()
```


レイアウトの名前を取得します。


**Returns:**
java.lang.String - レイアウトの名前。

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


レイアウトの名前を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | レイアウトに設定する名前。 |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


レイアウトの幅を取得します。


**Returns:**
double - レイアウトの幅。

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


レイアウトの幅を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | width | double | レイアウトに設定する幅。 |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


レイアウトの高さを取得します。


**Returns:**
double - レイアウトの高さ。

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


レイアウトの高さを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | height | double | レイアウトに設定する高さ。 |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


このオブジェクトが提供されたオブジェクトと等しいかどうかを確認します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | その他 | java.lang.Object | 比較対象のオブジェクト。 |
|

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

