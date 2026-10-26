---
title: "ProjectManagementViewInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "MS Project 문서에 대한 보기 정보를 나타냅니다."
type: docs
weight: 23
url: /ko/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

MS Project 문서에 대한 보기 정보를 나타냅니다.

ProjectManagementViewInfo 인터페이스는 GroupDocs.Viewer 구성 요소에서 MS Project 문서의 보기 정보를 액세스하고 조작하기 위한 계약을 정의합니다. 시작 및 종료 날짜와 기타 속성과 같은 정보를 검색하는 메서드를 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getStartDate()](#getStartDate--) | 프로젝트가 시작된 날짜와 시간을 검색합니다. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | 프로젝트의 시작 날짜와 시간을 설정합니다. |
| [getEndDate()](#getEndDate--) | 프로젝트가 완료될 날짜와 시간을 검색합니다. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | 프로젝트의 종료 날짜와 시간을 설정합니다. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


프로젝트가 시작된 날짜와 시간을 검색합니다.

**Returns:**
java.util.Date - 프로젝트의 시작 날짜와 시간.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


프로젝트의 시작 날짜와 시간을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startDate | java.util.Date | 설정할 새 시작 날짜와 시간. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


프로젝트가 완료될 날짜와 시간을 검색합니다.

**Returns:**
java.util.Date - 프로젝트의 종료 날짜와 시간.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


프로젝트의 종료 날짜와 시간을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| endDate | java.util.Date | 설정할 새 종료 날짜와 시간. |

