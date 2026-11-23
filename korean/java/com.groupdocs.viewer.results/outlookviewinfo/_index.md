---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Outlook 데이터 파일에 대한 보기 정보를 나타냅니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Outlook 데이터 파일에 대한 보기 정보를 나타냅니다.


OutlookViewInfo 인터페이스는 보기 정보를 액세스하고 조작하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소의 Outlook 데이터 파일에 대해. 이 구성 요소는 정보를 검색하는 메서드를 제공합니다.
예를 들어 폴더 목록 및 기타 속성들입니다.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFolders()](#getFolders--) | Outlook 데이터 파일에 포함된 폴더 목록을 검색합니다. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Outlook 데이터 파일에 포함된 폴더 목록을 설정합니다. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Outlook 데이터 파일에 포함된 폴더 목록을 검색합니다.


**Returns:**
java.util.List<java.lang.String> - 폴더 목록.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Outlook 데이터 파일에 포함된 폴더 목록을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 목록 | java.util.List<java.lang.String> | 폴더 목록. |
|

