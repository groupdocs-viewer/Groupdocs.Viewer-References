---
title: "OutlookViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Outlook データ ファイルのビュー情報を表します。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Outlook データ ファイルのビュー情報を表します。

OutlookViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内の Outlook データファイルに対するビュー情報へのアクセスと操作のための契約を定義します。フォルダーの一覧などの情報を取得するメソッドやその他のプロパティを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFolders()](#getFolders--) | Outlook データ ファイルに含まれるフォルダーのリストを取得します。 |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook データ ファイルに含まれるフォルダーのリストを設定します。 |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Outlook データ ファイルに含まれるフォルダーのリストを取得します。

**Returns:**
java.util.List<java.lang.String> - フォルダーのリスト。
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Outlook データ ファイルに含まれるフォルダーのリストを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| リスト | java.util.List<java.lang.String> | フォルダーのリスト。 |

