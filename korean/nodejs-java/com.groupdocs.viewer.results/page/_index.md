---
title: "페이지"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "볼 수 있는 단일 페이지를 나타냅니다."
type: docs
weight: 21
url: /ko/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

볼 수 있는 단일 페이지를 나타냅니다.

Page 인터페이스는 GroupDocs.Viewer 구성 요소에서 볼 수 있는 단일 페이지에 접근하고 조작하기 위한 계약을 정의합니다. 페이지 번호, 크기 및 기타 속성과 같은 정보를 검색하는 메서드를 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 워크시트 또는 페이지의 이름을 검색합니다. |
| [setName(String name)](#setName-java.lang.String-) | 워크시트 또는 페이지의 이름을 설정합니다. |
| [getNumber()](#getNumber--) | 페이지 번호를 검색합니다. |
| [setNumber(int number)](#setNumber-int-) | 페이지 번호를 설정합니다. |
| [isVisible()](#isVisible--) | 페이지 가시성 표시기를 검색합니다. |
| [setVisible(boolean visible)](#setVisible-boolean-) | 페이지 가시성 표시기를 설정합니다. |
| [getWidth()](#getWidth--) | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀)를 검색합니다. |
| [setWidth(int width)](#setWidth-int-) | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀)를 설정합니다. |
| [getHeight()](#getHeight--) | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)를 검색합니다. |
| [setHeight(int height)](#setHeight-int-) | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)를 설정합니다. |
| [getLines()](#getLines--) | 텍스트 추출이 활성화된 상태에서 JPG 또는 PNG로 볼 때 페이지에 포함된 라인을 검색합니다. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | 텍스트 추출이 활성화된 상태에서 JPG 및 PNG로 볼 때 페이지에 포함된 라인을 설정합니다. |
### getName() {#getName--}
```
public abstract String getName()
```


워크시트 또는 페이지의 이름을 검색합니다.

**Returns:**
java.lang.String - 워크시트 또는 페이지의 이름.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


워크시트 또는 페이지의 이름을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 워크시트 또는 페이지에 설정할 이름. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


페이지 번호를 검색합니다.

**Returns:**
int - 페이지 번호.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


페이지 번호를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 설정할 페이지 번호. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


페이지 가시성 표시기를 검색합니다.

**Returns:**
boolean - 페이지 가시성 표시기.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


페이지 가시성 표시기를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 보임 | boolean | 페이지가 보이면 true, 그렇지 않으면 false. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG 또는 PNG로 볼 때 페이지의 너비(픽셀)를 검색합니다.

**Returns:**
int - 페이지의 너비.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG 또는 PNG로 볼 때 페이지의 너비(픽셀)를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 페이지에 설정할 너비. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)를 검색합니다.

**Returns:**
int - 페이지의 높이.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| height | int | 페이지에 설정할 높이. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


텍스트 추출이 활성화된 상태에서 JPG 또는 PNG로 볼 때 페이지에 포함된 라인을 검색합니다.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - 페이지에 포함된 라인들.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


텍스트 추출이 활성화된 상태에서 JPG 및 PNG로 볼 때 페이지에 포함된 라인을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 라인 | java.util.List<com.groupdocs.viewer.results.Line> | 페이지에 설정할 라인 목록. |

