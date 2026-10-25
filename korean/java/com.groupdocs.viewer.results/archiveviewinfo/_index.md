---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "아카이브 파일에 대한 뷰 정보를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

아카이브 파일에 대한 뷰 정보를 나타냅니다.


ArchiveViewInfo 인터페이스는 아카이브 파일에 특화된 보기 정보를 검색하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서. 페이지 수, 차원 및 렌더링 옵션과 같은 세부 정보를 액세스하는 메서드를 제공합니다.
아카이브 파일에 특화된.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFolders()](#getFolders--) | 아카이브 파일에 포함된 폴더 목록을 검색합니다. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | 아카이브 파일에 포함된 폴더 목록을 설정합니다. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


아카이브 파일에 포함된 폴더 목록을 검색합니다.


**Returns:**
java.util.List<java.lang.String> - 폴더 목록.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


아카이브 파일에 포함된 폴더 목록을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 폴더 | java.util.List<java.lang.String> | 폴더 목록. |
|

