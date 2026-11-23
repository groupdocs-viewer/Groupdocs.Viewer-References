---
title: "PageSize"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "페이지 크기."
type: docs
weight: 42
url: /ko/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

페이지 크기.


PageSize 열거형은 GroupDocs.Viewer 구성 요소에서 다양한 페이지 크기를 나타냅니다.
사전 정의된 페이지 크기 집합을 제공하여 차원을 지정하는 데 사용할 수 있습니다.
다양한 문서 렌더링 시나리오에서 페이지의.


사용 예시:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | 기본값이며 지정되지 않은 페이지 크기. |
|
|  | [LETTER](#LETTER) | Letter 페이지의 크기(포인트)는 792 x 612입니다. |
|
|  | [LEDGER](#LEDGER) | A0 페이지의 크기(포인트)는 3371 x 2384입니다. |
|
|  | [A0](#A0) | A1 페이지의 크기(포인트)는 2384 x 1685입니다. |
|
|  | [A1](#A1) | A2 페이지의 크기(포인트)는 1684 x 1190입니다. |
|
|  | [A2](#A2) | A3 페이지의 크기(포인트)는 1190 x 842입니다. |
|
|  | [A3](#A3) | A3 페이지의 크기(포인트)는 1190 x 842입니다. |
|
|  | [A4](#A4) | A4 페이지의 크기(포인트)는 842 x 595입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


기본값이며 지정되지 않은 페이지 크기.
특정 페이지 크기가 지정되지 않은 경우 이 크기가 사용됩니다.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Letter 페이지의 크기(포인트)는 792 x 612입니다.
이 페이지 크기는 북미에서 편지와 문서에 일반적으로 사용됩니다.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


A0 페이지의 크기(포인트)는 3371 x 2384입니다.
이 큰 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### A0 {#A0}
```
public static final PageSize A0
```


A1 페이지의 크기(포인트)는 2384 x 1685입니다.
이 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### A1 {#A1}
```
public static final PageSize A1
```


A2 페이지의 크기(포인트)는 1684 x 1190입니다.
이 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### A2 {#A2}
```
public static final PageSize A2
```


A3 페이지의 크기(포인트)는 1190 x 842입니다.
이 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### A3 {#A3}
```
public static final PageSize A3
```


A3 페이지의 크기(포인트)는 1190 x 842입니다.
이 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### A4 {#A4}
```
public static final PageSize A4
```


A4 페이지의 크기(포인트)는 842 x 595입니다.
이 페이지 크기는 ISO 216 국제 표준의 일부입니다.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
