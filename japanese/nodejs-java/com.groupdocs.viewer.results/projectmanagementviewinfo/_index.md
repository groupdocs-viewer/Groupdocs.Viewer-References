---
title: "ProjectManagementViewInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "MS Project ドキュメントのビュー情報を表します。"
type: docs
weight: 23
url: /ja/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

MS Project ドキュメントのビュー情報を表します。

ProjectManagementViewInfo インターフェイスは、GroupDocs.Viewer コンポーネント内の MS Project ドキュメントのビュー情報へのアクセスと操作のための契約を定義します。開始日や終了日などの情報やその他のプロパティを取得するメソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getStartDate()](#getStartDate--) | プロジェクトが開始した日時を取得します。 |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | プロジェクトの開始日時を設定します。 |
| [getEndDate()](#getEndDate--) | プロジェクトが完了する日時を取得します。 |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | プロジェクトの終了日時を設定します。 |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


プロジェクトが開始した日時を取得します。

**Returns:**
java.util.Date - プロジェクトの開始日時。
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


プロジェクトの開始日時を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startDate | java.util.Date | 設定する新しい開始日時。 |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


プロジェクトが完了する日時を取得します。

**Returns:**
java.util.Date - プロジェクトの終了日時。
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


プロジェクトの終了日時を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| endDate | java.util.Date | 設定する新しい終了日時。 |

