---
title: "Layout"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CAD 도면에 포함된 레이아웃을 나타냅니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

CAD 도면에 포함된 레이아웃을 나타냅니다.


Layout 인터페이스는 CAD 도면 내 레이아웃에 액세스하고 조작하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서. 이 구성 요소는 레이아웃 이름과 같은 정보를 검색하는 메서드를 제공합니다.
치수 및 기타 속성들.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 레이아웃의 이름을 검색합니다. |
|
|  | [setName(String name)](#setName-java.lang.String-) | 레이아웃의 이름을 설정합니다. |
|
|  | [getWidth()](#getWidth--) | 레이아웃의 너비를 검색합니다. |
|
|  | [setWidth(double width)](#setWidth-double-) | 레이아웃의 너비를 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 레이아웃의 높이를 검색합니다. |
|
|  | [setHeight(double height)](#setHeight-double-) | 레이아웃의 높이를 설정합니다. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 이 객체가 제공된 객체와 같은지 확인합니다. |
|
### getName() {#getName--}
```
public abstract String getName()
```


레이아웃의 이름을 검색합니다.


**Returns:**
java.lang.String - 레이아웃의 이름.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


레이아웃의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 레이아웃에 설정할 이름. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


레이아웃의 너비를 검색합니다.


**Returns:**
double - 레이아웃의 너비.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


레이아웃의 너비를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | width | double | 레이아웃에 설정할 너비. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


레이아웃의 높이를 검색합니다.


**Returns:**
double - 레이아웃의 높이.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


레이아웃의 높이를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | height | double | 레이아웃에 설정할 높이. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


이 객체가 제공된 객체와 같은지 확인합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 기타 | java.lang.Object | 비교할 객체. |
|

**Returns:**
boolean -  true 이면 객체가 동일하고,  false 이면 그렇지 않습니다.

