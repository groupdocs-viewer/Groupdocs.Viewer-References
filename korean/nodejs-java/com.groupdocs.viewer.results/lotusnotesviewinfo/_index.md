---
title: "LotusNotesViewInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Lotus Notes 데이터베이스 저장소에 대한 보기 정보를 나타냅니다."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Lotus Notes 데이터베이스 저장소에 대한 보기 정보를 나타냅니다.

LotusNotesViewInfo 인터페이스는 GroupDocs.Viewer 구성 요소에서 Lotus Notes 데이터베이스 저장소에 대한 보기 정보를 액세스하고 조작하기 위한 계약을 정의합니다. 이 인터페이스는 노트 수와 같은 정보를 검색하는 메서드 및 기타 속성을 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | 저장소에 있는 노트 수를 검색합니다. |
| [setNotesCount(int count)](#setNotesCount-int-) | 저장소에 있는 노트 수를 설정합니다. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


저장소에 있는 노트 수를 검색합니다.

**Returns:**
int - 저장소에 있는 노트 수.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


저장소에 있는 노트 수를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 카운트 | int | 저장소에 있는 노트 수. |

