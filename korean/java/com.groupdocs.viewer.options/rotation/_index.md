---
title: "Rotation"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "시계 방향으로 페이지 회전 각도를 포함합니다."
type: docs
weight: 45
url: /ko/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

페이지 회전 각도(시계 방향)를 포함합니다.


Rotation 열거형은 GroupDocs.Viewer 구성 요소에서 페이지에 대한 다양한 회전 각도를 나타냅니다.
회전 각도를 지정하는 데 사용할 수 있는 미리 정의된 회전 옵션 집합을 제공합니다.
다양한 문서 보기 또는 변환 시나리오에서 페이지를 렌더링하기 위해.


사용 예시:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | 90도 페이지 회전. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | 180도 페이지 회전. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | 270도 페이지 회전. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90도 페이지 회전.
이 회전은 페이지의 시계 방향 90도 회전을 나타냅니다.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180도 페이지 회전.
이 회전은 페이지의 시계 방향 180도 회전을 나타냅니다.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270도 페이지 회전.
이 회전은 페이지의 시계 방향 270도 회전을 나타냅니다.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
