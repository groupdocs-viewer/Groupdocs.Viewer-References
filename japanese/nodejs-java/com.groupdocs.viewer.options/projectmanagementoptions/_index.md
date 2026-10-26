---
title: "ProjectManagementOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "プロジェクト管理ファイルのレンダリングオプションを提供します。"
type: docs
weight: 27
url: /ja/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

プロジェクト管理ファイルのレンダリングオプションを提供します。

ProjectManagementOptions クラスは、GroupDocs.Viewer コンポーネントでプロジェクト管理ファイル（Microsoft Project など）のレンダリングを制御するために使用できるさまざまな設定やパラメータをカプセル化します。詳細については、[documentation][] を参照してください。

使用例:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | ProjectManagementOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPageSize()](#getPageSize--) | 出力ページサイズを取得します。 |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 出力ページサイズを設定します。 |
| [getTimeUnit()](#getTimeUnit--) | 時間単位を取得します。 |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | 時間単位を取得します。 |
| [getStartDate()](#getStartDate--) | 出力に含めるガントチャートビューの開始日を取得します。 |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | 出力に含めるガントチャートビューの開始日を設定します。 |
| [getEndDate()](#getEndDate--) | 出力に含めるガントチャートビューの終了日を取得します。 |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | 出力に含めるガントチャートビューの終了日を設定します。 |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


ProjectManagementOptions クラスの新しいインスタンスを初期化します。

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


出力ページサイズを取得します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


出力ページサイズを設定します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 出力ページサイズ。 |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


時間単位を取得します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


時間単位を取得します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | 時間単位。 |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


出力に含めるガントチャートビューの開始日を取得します。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - ガントチャートビューの開始日。
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


出力に含めるガントチャートビューの開始日を設定します。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date | ガントチャートビューの開始日。 |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


出力に含めるガントチャートビューの終了日を取得します。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - ガントチャートビューの終了日。
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


出力に含めるガントチャートビューの終了日を設定します。

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Date | ガントチャートビューの終了日。 |

