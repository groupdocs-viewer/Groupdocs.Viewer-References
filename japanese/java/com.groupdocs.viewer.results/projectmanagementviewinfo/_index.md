---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "MS Projectドキュメントのビュー情報を表します。"
type: docs
weight: 25
url: /ja/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

MS Projectドキュメントのビュー情報を表します。


ProjectManagementViewInfo インターフェイスは、ビュー情報へのアクセスおよび操作のための契約を定義します
GroupDocs.Viewer コンポーネントの MS Project ドキュメント用です。情報を取得するためのメソッドを提供します
開始日と終了日、およびその他のプロパティなどです。


使用例:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | プロジェクトが開始された日時を取得します。 |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | プロジェクトの開始日時を設定します。 |
|
|  | [getEndDate()](#getEndDate--) | プロジェクトの完了予定日時を取得します。 |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | プロジェクトの終了日時を設定します。 |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


プロジェクトが開始された日時を取得します。


**Returns:**
java.util.Date - プロジェクトの開始日時です。

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


プロジェクトの開始日時を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | startDate | java.util.Date | 設定する新しい開始日時です。 |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


プロジェクトの完了予定日時を取得します。


**Returns:**
java.util.Date - プロジェクトの終了日時です。

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


プロジェクトの終了日時を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | endDate | java.util.Date | 設定する新しい終了日時です。 |
|

