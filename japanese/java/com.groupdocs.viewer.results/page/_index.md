---
title: "ページ"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "表示可能な単一ページを表します。"
type: docs
weight: 23
url: /ja/java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

表示可能な単一ページを表します。


Page インターフェイスは、単一ページにアクセスし操作するための契約を定義します。
GroupDocs.Viewer コンポーネントで表示できるページです。取得するためのメソッドを提供します。
ページ番号、サイズ、その他のプロパティなどの情報。


使用例:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is PageImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | ワークシートまたはページの名前を取得します。 |
|
|  | [setName(String name)](#setName-java.lang.String-) | ワークシートまたはページの名前を設定します。 |
|
|  | [getNumber()](#getNumber--) | ページ番号を取得します。 |
|
|  | [setNumber(int number)](#setNumber-int-) | ページ番号を設定します。 |
|
|  | [isVisible()](#isVisible--) | ページの表示状態インジケータを取得します。 |
|
|  | [setVisible(boolean visible)](#setVisible-boolean-) | ページの表示状態インジケータを設定します。 |
|
|  | [getWidth()](#getWidth--) | JPG または PNG として表示する際のページ幅（ピクセル）を取得します。 |
|
|  | [setWidth(int width)](#setWidth-int-) | JPG または PNG として表示する際のページ幅（ピクセル）を設定します。 |
|
|  | [getHeight()](#getHeight--) | JPG または PNG として表示する際のページの高さ（ピクセル）を取得します。 |
|
|  | [setHeight(int height)](#setHeight-int-) | JPG または PNG として表示する際のページの高さ（ピクセル）を設定します。 |
|
|  | [getLines()](#getLines--) | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を取得します。 |
|
|  | [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を設定します。 |
|
### getName() {#getName--}
```
public abstract String getName()
```


ワークシートまたはページの名前を取得します。


**Returns:**
java.lang.String - ワークシートまたはページの名前。

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


ワークシートまたはページの名前を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | ワークシートまたはページに設定する名前。 |
|

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


ページ番号を取得します。


**Returns:**
int - ページ番号。

### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


ページ番号を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | number | int | 設定するページ番号。 |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


ページの表示状態インジケータを取得します。


**Returns:**
boolean - ページの表示状態インジケータ。

### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


ページの表示状態インジケータを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | visible | boolean | ページが表示されている場合は true、そうでない場合は false。 |
|

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG または PNG として表示する際のページ幅（ピクセル）を取得します。


**Returns:**
int - ページの幅。

### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG または PNG として表示する際のページ幅（ピクセル）を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | width | int | ページに設定する幅。 |
|

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG または PNG として表示する際のページの高さ（ピクセル）を取得します。


**Returns:**
int - ページの高さ。

### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG または PNG として表示する際のページの高さ（ピクセル）を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | height | int | ページに設定する高さ。 |
|

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を取得します。


**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - ページに含まれる行。

### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | lines | java.util.List<com.groupdocs.viewer.results.Line> | ページに設定する行のリスト。 |
|

