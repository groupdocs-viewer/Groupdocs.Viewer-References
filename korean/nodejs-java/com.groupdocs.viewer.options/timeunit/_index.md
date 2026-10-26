---
title: "TimeUnit"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "프로젝트 기간의 시간 단위입니다."
type: docs
weight: 47
url: /ko/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

프로젝트 기간의 시간 단위입니다.

TimeUnit 열거형은 GroupDocs.Viewer 구성 요소에서 프로젝트 기간을 지정하기 위한 다양한 시간 단위를 나타냅니다. 이는 일, 월 등과 같이 프로젝트 기간을 표현하고 계산하는 데 사용할 수 있는 미리 정의된 시간 단위 집합을 제공합니다. 자세한 내용은 [documentation][].

예시 사용법:

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | 알 수 없는 시간 척도. |
| [DAYS](#DAYS) | 일 시간 척도. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | 월의 3분의 1 시간 척도. |
| [MONTHS](#MONTHS) | 월 시간 척도. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


알 수 없는 시간 척도. 이 시간 단위는 알 수 없거나 지정되지 않은 시간 척도를 나타냅니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


일 시간 척도. 이 시간 단위는 1일 간격을 나타냅니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


월의 3분의 1 시간 척도. 이 시간 단위는 한 달의 1/3 간격을 나타냅니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


월 시간 척도. 이 시간 단위는 1개월 간격을 나타냅니다.

자세한 내용은 [documentation][].


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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
