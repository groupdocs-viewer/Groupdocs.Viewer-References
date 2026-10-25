---
title: "TimeUnit"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "プロジェクト期間の時間単位。"
type: docs
weight: 47
url: /ja/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

プロジェクト期間の時間単位。


TimeUnit 列挙型は、GroupDocs.Viewer コンポーネントでプロジェクトの期間を指定するためのさまざまな時間単位を表します。
プロジェクトの期間を表現および計算するために使用できる、事前定義された時間単位のセットを提供します、
例えば日、月などです。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) を参照してください。


使用例:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | 不明な時間スケールです。 |
|
|  | [DAYS](#DAYS) | 日単位の時間スケールです。 |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | 月の3分の1単位の時間スケールです。 |
|
|  | [MONTHS](#MONTHS) | 月単位の時間スケールです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


不明な時間スケールです。
この時間単位は不明または未指定の時間スケールを表します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) を参照してください。


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


日単位の時間スケールです。
この時間単位は1日間隔を表します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) を参照してください。


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


月の3分の1単位の時間スケールです。
この時間単位は月の3分の1間隔を表します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) を参照してください。


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


月単位の時間スケールです。
この時間単位は1か月間隔を表します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) を参照してください。


### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
