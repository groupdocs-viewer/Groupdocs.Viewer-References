---
title: "TimeUnit"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "项目持续时间的时间单位。"
type: docs
weight: 47
url: /zh/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

项目持续时间的时间单位。

TimeUnit 枚举表示在 GroupDocs.Viewer 组件中用于指定项目持续时间的不同时间单位。它提供了一组预定义的时间单位，可用于表示和计算项目的持续时间，例如天、月等。详情请参阅 [documentation][].

示例用法：

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
## 字段

| 字段 | 描述 |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | 未知的时间尺度。 |
| [DAYS](#DAYS) | 天时间尺度。 |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | 月的三分之一时间尺度。 |
| [MONTHS](#MONTHS) | 月时间尺度。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


未知的时间尺度。此时间单位表示未知或未指定的时间尺度。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


天时间尺度。此时间单位表示一天的间隔。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


月的三分之一时间尺度。此时间单位表示一个月的三分之一间隔。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


月时间尺度。此时间单位表示一个月的间隔。

有关详细信息，请参阅[文档][].


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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
