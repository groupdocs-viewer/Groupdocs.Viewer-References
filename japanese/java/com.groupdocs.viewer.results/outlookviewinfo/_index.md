---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Outlookデータファイルのビュー情報を表します。"
type: docs
weight: 22
url: /ja/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Outlookデータファイルのビュー情報を表します。


OutlookViewInfoインターフェイスは、ビュー情報へのアクセスと操作のための契約を定義します。
GroupDocs.ViewerコンポーネントのOutlookデータファイル用です。情報を取得するメソッドを提供します。
フォルダーのリストやその他のプロパティなど。


使用例:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFolders()](#getFolders--) | Outlook データ ファイルに含まれるフォルダーのリストを取得します。 |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook データ ファイルに含まれるフォルダーのリストを設定します。 |
|
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
|  | リスト | java.util.List<java.lang.String> | フォルダーのリスト。 |
|

