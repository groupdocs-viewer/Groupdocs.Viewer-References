---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Lotus Notes 데이터베이스 저장소에 대한 보기 정보를 나타냅니다."
type: docs
weight: 19
url: /ko/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes 데이터베이스 저장소에 대한 보기 정보를 나타냅니다.


LotusNotesViewInfo 인터페이스는 뷰 정보를 액세스하고 조작하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서 Lotus Notes 데이터베이스 저장소를 위해 사용됩니다. 정보를 검색하는 메서드를 제공합니다.
예를 들어 노트 수 및 기타 속성 등.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | 스토리지의 노트 수를 검색합니다. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | 스토리지의 노트 수를 설정합니다. |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


스토리지의 노트 수를 검색합니다.


**Returns:**
int - 스토리지의 노트 수.

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


스토리지의 노트 수를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 수 | int | 스토리지의 노트 수. |
|

