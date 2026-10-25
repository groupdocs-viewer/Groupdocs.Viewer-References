---
title: "レイヤー"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "CAD図面に含まれるレイヤーを表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

CAD図面に含まれるレイヤーを表します。


Layer インターフェイスは、CAD 図面内のレイヤーにアクセスし操作するための契約を定義します。
GroupDocs.Viewer コンポーネント内です。レイヤー名などの情報を取得するメソッドを提供します、
可視性やその他のプロパティ。


使用例:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | レイヤーの名前を取得します。 |
|
|  | [setName(String name)](#setName-java.lang.String-) | レイヤーの名前を設定します。 |
|
|  | [isVisible()](#isVisible--) | レイヤーの可視性を確認します。 |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | レイヤーの可視性を設定します。 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | このオブジェクトが提供されたオブジェクトと等しいかどうかを確認します。 |
|
### getName() {#getName--}
```
public abstract String getName()
```


レイヤーの名前を取得します。


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - レイヤーの名前。

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


レイヤーの名前を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | レイヤーの新しい名前です。 |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


レイヤーの可視性を確認します。


オフまたはフリーズされた CAD 図面レイヤーは非表示になります。
非表示のレイヤーをレンダリングするには、[CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-) オプションを使用します。


**Returns:**
boolean -  true  if the layer is visible,  false  otherwise.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


レイヤーの可視性を設定します。


もし
true
、レイヤーは表示されます。もし
false
、非表示になります。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | isVisible | boolean | レイヤーを表示するかどうか。 |
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

