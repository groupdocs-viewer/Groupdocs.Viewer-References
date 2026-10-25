---
title: "TimeUnit"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "프로젝트 기간의 시간 단위."
type: docs
weight: 47
url: /ko/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

프로젝트 기간의 시간 단위.


TimeUnit 열거형은 GroupDocs.Viewer 구성 요소에서 프로젝트 기간을 지정하기 위한 다양한 시간 단위를 나타냅니다.
프로젝트 기간을 나타내고 계산하는 데 사용할 수 있는 미리 정의된 시간 단위 집합을 제공합니다,
예: 일, 월 등.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 를 참조하십시오.


사용 예시:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | 알 수 없는 시간 척도. |
|
|  | [DAYS](#DAYS) | 일 시간 척도. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | 한 달의 3분의 1 시간 척도. |
|
|  | [MONTHS](#MONTHS) | 개월 시간 척도. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


알 수 없는 시간 척도.
이 시간 단위는 알 수 없거나 지정되지 않은 시간 척도를 나타냅니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 를 참조하십시오.


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


일 시간 척도.
이 시간 단위는 하루 간격을 나타냅니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 를 참조하십시오.


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


한 달의 3분의 1 시간 척도.
이 시간 단위는 한 달의 3분의 1 간격을 나타냅니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 를 참조하십시오.


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


개월 시간 척도.
이 시간 단위는 한 달 간격을 나타냅니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 를 참조하십시오.


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
