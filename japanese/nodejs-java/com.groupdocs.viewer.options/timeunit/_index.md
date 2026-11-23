---
title: "TimeUnit"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "プロジェクト期間の時間単位です。"
type: docs
weight: 47
url: /ja/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

プロジェクト期間の時間単位です。

TimeUnit 列挙型は、GroupDocs.Viewer コンポーネントでプロジェクトの期間を指定するためのさまざまな時間単位を表します。日数や月数など、プロジェクトの期間を表現・計算するために使用できる事前定義された時間単位のセットを提供します。詳細については、[documentation][] を参照してください。

使用例:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## フィールド

| フィールド | 説明 |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | 不明な時間スケールです。 |
| [DAYS](#DAYS) | 日単位の時間スケール。 |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | 月の 1/3 の時間スケール。 |
| [MONTHS](#MONTHS) | 月単位の時間スケール。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


不明な時間スケールです。この時間単位は未知または未指定の時間スケールを表します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


日単位の時間スケールです。この時間単位は 1 日の間隔を表します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


月の 1/3 の時間スケールです。この時間単位は月の 1/3 の間隔を表します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


月単位の時間スケールです。この時間単位は 1 ヶ月の間隔を表します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

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
