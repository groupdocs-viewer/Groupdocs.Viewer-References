---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Lotus Notesデータベースストレージのビュー情報を表します。"
type: docs
weight: 19
url: /ja/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notesデータベースストレージのビュー情報を表します。


LotusNotesViewInfoインターフェイスは、ビュー情報へのアクセスと操作のための契約を定義します。
GroupDocs.ViewerコンポーネントのLotus Notesデータベースストレージ用です。情報を取得するメソッドを提供します。
ノート数やその他のプロパティなど。


使用例:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | ストレージ内のノート数を取得します。 |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | ストレージ内のノート数を設定します。 |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


ストレージ内のノート数を取得します。


**Returns:**
int - ストレージ内のノート数。

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


ストレージ内のノート数を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | カウント | int | ストレージ内のノート数。 |
|

