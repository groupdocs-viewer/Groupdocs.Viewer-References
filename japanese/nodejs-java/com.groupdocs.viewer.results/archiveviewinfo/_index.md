---
title: "ArchiveViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "アーカイブ ファイルのビュー情報を表します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

アーカイブ ファイルのビュー情報を表します。

ArchiveViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内のアーカイブ ファイルに固有のビュー情報を取得するための契約を定義します。ページ数、寸法、アーカイブ ファイル固有のレンダリング オプションなどの詳細にアクセスするメソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFolders()](#getFolders--) | アーカイブ ファイルに含まれるフォルダーの一覧を取得します。 |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | アーカイブ ファイルに含まれるフォルダーの一覧を設定します。 |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


アーカイブ ファイルに含まれるフォルダーの一覧を取得します。

**Returns:**
java.util.List<java.lang.String> - フォルダーのリスト。
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


アーカイブ ファイルに含まれるフォルダーの一覧を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フォルダー | java.util.List<java.lang.String> | フォルダーのリスト。 |

