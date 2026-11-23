---
title: "LotusNotesViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Lotus Notes データベース ストレージのビュー情報を表します。"
type: docs
weight: 19
url: /ja/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes データベース ストレージのビュー情報を表します。

LotusNotesViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内の Lotus Notes データベースストレージに対するビュー情報へのアクセスと操作のための契約を定義します。ノート数などの情報を取得するメソッドやその他のプロパティを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | ストレージ内のノート数を取得します。 |
| [setNotesCount(int count)](#setNotesCount-int-) | ストレージ内のノート数を設定します。 |
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
| count | int | ストレージ内のノート数。 |

