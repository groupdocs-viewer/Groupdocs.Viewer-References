---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "프로젝트 관리 파일을 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 27
url: /ko/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

프로젝트 관리 파일을 렌더링하기 위한 옵션을 제공합니다.


ProjectManagementOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다
프로젝트 관리 파일(예: Microsoft Project 등)의 렌더링을 제어합니다
GroupDocs.Viewer 구성 요소에서.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/)를 참조하세요.


사용 예시:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | 새 인스턴스를 초기화합니다. |
ProjectManagementOptions
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | 출력 페이지 크기를 가져옵니다. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 출력 페이지 크기를 설정합니다. |
|
|  | [getTimeUnit()](#getTimeUnit--) | 시간 단위를 가져옵니다. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | 시간 단위를 가져옵니다. |
|
|  | [getStartDate()](#getStartDate--) | 출력에 포함될 Gantt Chart View의 시작 날짜를 가져옵니다. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | 출력에 포함될 Gantt Chart View의 시작 날짜를 설정합니다. |
|
|  | [getEndDate()](#getEndDate--) | 출력에 포함될 Gantt Chart View의 종료 날짜를 가져옵니다. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | 출력에 포함될 Gantt Chart View의 종료 날짜를 설정합니다. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


새 인스턴스를 초기화합니다.
ProjectManagementOptions
클래스.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


출력 페이지 크기를 가져옵니다.


코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size) 을(를) 참조하세요.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


출력 페이지 크기를 설정합니다.


코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size) 을(를) 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 출력 페이지 크기. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


시간 단위를 가져옵니다.


코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 을(를) 참조하세요.


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


시간 단위를 가져옵니다.


코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit) 을(를) 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | 시간 단위. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


출력에 포함될 Gantt Chart View의 시작 날짜를 가져옵니다.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) 을(를) 참조하세요.


**Returns:**
java.util.Date - Gantt Chart View의 시작 날짜.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


출력에 포함될 Gantt Chart View의 시작 날짜를 설정합니다.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) 을(를) 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.Date | Gantt Chart View의 시작 날짜. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


출력에 포함될 Gantt Chart View의 종료 날짜를 가져옵니다.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) 을(를) 참조하세요.


**Returns:**
java.util.Date - Gantt Chart View의 종료 날짜.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


출력에 포함될 Gantt Chart View의 종료 날짜를 설정합니다.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
코드 샘플은 [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates) 을(를) 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.Date | Gantt Chart View의 종료 날짜. |
|

